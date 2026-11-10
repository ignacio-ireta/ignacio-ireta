# José Ignacio Esparza Ireta

**Applied AI & MLOps Engineer (forward-deployed).** I take enterprise ML and LLM systems from notebook to operated pipeline, with the tests, monitoring, and documentation that let another team run them.

Currently an Applications, Data & AI Consultant at Kyndryl in Mexico City. **Relocating to Norway** (Oslo · Bergen · Stavanger · Trondheim · Drammen) and open to applied AI, MLOps, and forward-deployed engineering roles.

[Portfolio](https://ignacio-ireta.github.io) · [Case studies](https://ignacio-ireta.github.io/projects/enterprise-ml-delivery/) · [LinkedIn](https://www.linkedin.com/in/ignacio-ireta) · [Email](mailto:ignacio.ireta@outlook.com)

## What I do at work

| Sector | What I built | Result |
|---|---|---|
| **Energy** (natural gas utility) | Rebuilt an undocumented R non-payment model (XGBoost) as config-driven Python on AWS SageMaker Pipelines, with Terraform and MLflow | 10× the data in about ⅓ of the compute runtime · ~240 features over ~10M records · 114+ tests and PSI/KS/chi-squared drift checks where none existed |
| **Enterprise knowledge engineering** | Formalized shared business terminology as an RDF/OWL ontology (Turtle) consumed in-context by an LLM agent, plus a zero-install browser editor for `.ttl` files | Cross-department answer inconsistency removed in the proof of concept; in-context ontology gave more consistent answers than a retrieval-based design |
| **Pharmaceutical distribution** | As-is AI architecture map, a Data & AI Governance Center of Excellence blueprint on Microsoft Purview, and an AI engineering curriculum for software engineers | Facilitated the cross-stakeholder decision sessions that established the client's governance CoE |

Client names and internals are left out. The [case studies](https://ignacio-ireta.github.io/projects/enterprise-ml-delivery/) cover the first two in detail.

## Things you can run

| Project | What it is | Try it |
|---|---|---|
| **[Multi-City Convenience Map](https://github.com/ignacio-ireta/cdmx-convenience-map)** | Geospatial scoring engine for **five Norwegian cities** and two Mexican ones. Typed Python CLI, Kartverket and OpenStreetMap data, optional Valhalla routing, React + Leaflet frontend with no backend | [Oslo](https://ignacio-ireta.github.io/projects/cdmx-map/?city=oslo) · [Bergen](https://ignacio-ireta.github.io/projects/cdmx-map/?city=bergen) · [Stavanger](https://ignacio-ireta.github.io/projects/cdmx-map/?city=stavanger) · [Trondheim](https://ignacio-ireta.github.io/projects/cdmx-map/?city=trondheim) · [Drammen](https://ignacio-ireta.github.io/projects/cdmx-map/?city=drammen) |
| **[dogma](https://github.com/ignacio-ireta/dogma)** | Local-first practice platform for ML, deep learning, LLM engineering, inference, SQL, and ML system design: 175 topics, 251 verified problems, FSRS spaced review, sandboxed grader, local-model tutor. FastAPI + React | [Interactive demo](https://ignacio-ireta.github.io/projects/dogma/) (graded in your browser with Pyodide) |
| **[dossier](https://github.com/ignacio-ireta/dossier)** | Local-first context suite for AI agents: converts and indexes a project's documents and meeting recordings, then serves them through a read-only **MCP server** with citations. Policy gate, speaker-aware meeting summaries, DOCX/PPTX/PDF rendering | Source |
| **[ETF Portfolio Research](https://github.com/ignacio-ireta/etf-portfolio-research)** | Reproducible portfolio optimization and walk-forward backtesting, with no-lookahead and leakage regression tests, golden-file metrics, a model card, and resumable runs | [Interactive report](https://ignacio-ireta.github.io/projects/etf-portfolio-research/) |
| **Reed** | Privacy-first Android speed-reading app in Kotlin and Jetpack Compose. Own binary MOBI parser, 105 unit tests, strict detekt, localized in **Norwegian**, English, Spanish, and French | [Google Play](https://play.google.com/store/apps/details?id=com.reed.rsvp) |

Smaller work: [AIIRG](https://github.com/ignacio-ireta/AIIRG) (Gemini research-to-report workflow), [VADT](https://github.com/ignacio-ireta/vadt) (ECAPA-TDNN accent identification), [glycan–lectin network analysis](https://github.com/ignacio-ireta/network_analysis), and [evolutionary computation](https://github.com/ignacio-ireta/evolutionary-computation-and-genetic-algorithms) (CMA-ES, genetic algorithms, tabu search, simulated annealing).

## How I build

- `uv`, pinned lockfiles, and typed Python (`ruff`, `mypy`, Pydantic) by default
- Unit, integration, end-to-end, and golden-file tests; CI on every push
- Fetch, compute, and render kept separable, with a written data contract between them
- Failures treated as data: structured errors, resumable runs, atomic writes
- Documentation written for the person who inherits the system

## Toolkit

- **ML & MLOps:** Python, SQL, XGBoost, scikit-learn, pandas, AWS SageMaker Pipelines, MLflow, drift monitoring (PSI, KS, chi-squared)
- **Cloud & infrastructure:** AWS, Azure, Terraform, Docker, GitHub Actions
- **LLM & knowledge systems:** LLM agents, MCP servers, RDF/OWL/Turtle ontologies, local models (Ollama, llama.cpp), evaluation of in-context versus retrieval designs
- **Product engineering:** FastAPI, React, TypeScript, Kotlin, Jetpack Compose
- **Governance:** Microsoft Purview, model cards, data contracts

## Background

- **M.S. Computer Science**, Georgia Institute of Technology (OMSCS). Admitted; part-time from Spring 2027 alongside full-time work
- **B.Sc. Information Technologies for Science** (data science track), UNAM, ENES Morelia. Grade average 9.28/10
- **Certifications:** Azure Fundamentals (AZ-900), Azure AI Fundamentals (AI-900), Azure Data Fundamentals (DP-900), Google Cloud Digital Leader, DataCamp Associate Data Engineer
- **Languages:** Spanish (native) · English (C1, TOEFL iBT 110/120) · Norwegian Bokmål (A2–B1, studying actively)

Jeg lærer norsk og tar gjerne en prat. I am also learning violin, which is humbling in exactly the right way.
