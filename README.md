# Hi, I'm Elissa Esterlein

### Portfolio & resume: **[eesterlein.github.io](https://eesterlein.github.io/)**

Data analyst and developer in Gunnison, Colorado. I build AI tools and automated data workflows that people use in their daily work: a Claude Vision photo classifier used by appraisal staff every day, a private RAG chatbot, multi-model LLM evaluations, and pipelines that rebuild and republish themselves when new data lands. My favorite problems start with a manual step that shouldn't exist.

**Focus:** LLM APIs and AI automation · RAG · data pipelines · full-stack web apps · GIS

## Flagship project

### [Gunnison County Assessor Map](https://github.com/Eesterlein/assessor-map) · [live app](http://165.232.147.15)

A full-stack GIS platform that lets non-technical users build their own interactive maps with no GIS software. Upload a CSV or Excel file and it joins to parcel geometries by account number. Ingest shapefiles, GeoPackages, or GeoJSON straight into PostGIS. Configure layers, styles, and multiple maps from an admin panel. Wildfire detections refresh every 30 minutes.

`React` `TypeScript` `Node.js` `MapLibre GL JS` `PostgreSQL/PostGIS` `OGC API` `GDAL` `Docker` `nginx`

## AI & automation

| Project | What it does | Stack |
|---|---|---|
| [Appraiser Photo Processor](https://github.com/Eesterlein/Appraiser-Photo-Processor) | Multimodal AI in daily use: reads each photo's GPS and compass data, matches it to a parcel, classifies it with Claude Vision, and renames it to office standards for about $0.002 per photo | Python, Claude API, PyInstaller |
| [Private RAG Chatbot](https://github.com/Eesterlein/Building-Local-LLMs-for-Private-Workflows) | Retrieval-augmented chatbot over internal policy documents, plus an on-device coding assistant. Fully local, so sensitive data never leaves the machine | Python, LlamaIndex, Ollama |
| [Multi-Model Website Audit](https://github.com/Eesterlein/gunnison-assessor-audit) · [live](https://eesterlein.github.io/gunnison-assessor-audit/) | The same prompt and rubric run through ChatGPT, Gemini, and Claude across 24 counties, merged into one ranked action plan | OpenAI, Anthropic, Gemini |
| [Land Attributes Dashboard](https://github.com/Eesterlein/gunnison-land-attributes-demo) · [live](https://eesterlein.github.io/gunnison-land-attributes-demo/) | 17,500-parcel review tool. Uploading new data triggers a GitHub Actions pipeline that cleans it and republishes the site in about two minutes | Python, GitHub Actions, MapLibre |
| [Airport Tracker](https://github.com/Eesterlein/gunnison-airport-tracker) | Pulls the OpenSky REST API every hour and logs repeat aircraft to PostgreSQL, unattended | Node.js, REST APIs, PostgreSQL |
| [AI Demos](https://github.com/Eesterlein/gunnison_ai_demos) | Streamlit prototypes, including a GPT-based correspondence assistant | Python, OpenAI API, Streamlit |

## More apps & data projects

| Project | What it is | Stack |
|---|---|---|
| [Permit Portal](https://github.com/Eesterlein/gunnison-permit-portal) | Building-permit search and staff portal for four jurisdictions; learns each jurisdiction's CSV/Excel layout | React, Node/Express, PostgreSQL, AWS |
| [Property Eye](https://github.com/Eesterlein/gunnison-property-eye) | Satellite change detection to flag new construction (in development) | FastAPI, Earth Engine, PostGIS |
| [Building Stock Dashboard](https://github.com/Eesterlein/gunnison-building-stock) · [live](https://eesterlein.github.io/gunnison-building-stock/) | Analysis of 18,000+ county building records | JavaScript, SVG |
| [Who Owns Colorado?](https://github.com/Eesterlein/colorado-land-ownership) · [live](https://eesterlein.github.io/colorado-land-ownership/) | Public vs. private land ownership statewide | Python, GeoPandas |
| [Property Tax Calculator](https://github.com/Eesterlein/gunnison-county-property-tax-calculator) · [live](https://eesterlein.github.io/gunnison-county-property-tax-calculator/) | How assessed values and mill levies become a tax bill | JavaScript |

## Tools

**AI:** Anthropic Claude API · OpenAI API · Gemini · vision classification · prompt engineering · RAG · embeddings · LlamaIndex · Ollama
**Automation:** GitHub Actions · scheduled API ingestion · ETL · REST APIs / JSON
**Code:** Python · JavaScript/TypeScript · React · Node.js/Express · SQL (SQL Server, PostgreSQL, Access)
**GIS & infra:** PostGIS · GDAL · MapLibre GL JS · Docker · nginx · AWS

## Elsewhere

[Portfolio site](https://eesterlein.github.io/) · [LinkedIn](https://www.linkedin.com/in/elissa-esterlein-a80857369/) · [Tableau Public](https://public.tableau.com/app/profile/elissa.esterlein/vizzes) · [Kaggle](https://www.kaggle.com/elissaesterlein)

<sub>County-related projects here are independent work built from publicly available data. They are not official products of the Gunnison County Assessor's Office or Gunnison County.</sub>
