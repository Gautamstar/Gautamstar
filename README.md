<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&duration=3000&pause=1000&color=7AA2F7&center=true&vCenter=true&width=650&lines=Hi%2C+I'm+Gautam+Singh;Software+Engineer;Backend%2C+data%2C+and+ML+systems;I+ship+things+people+use" alt="Typing SVG" />

<p>
  <a href="https://gautamstar.github.io/portfolio/"><img src="https://img.shields.io/badge/Portfolio-7AA2F7?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/gautam-singh-cs/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:gautamsingh2189@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<img src="https://raw.githubusercontent.com/Gautamstar/Gautamstar/main/assets/pipeline.svg" alt="Ingest, store, transform, model, serve" width="100%" />

</div>

---

### About

```python
class Gautam:
    role      = "Software Engineer: backend, data, and ML systems"
    location  = "Guelph, Ontario, Canada"
    education = "Bachelor of Computer Science (Honours), Conestoga College, 2025"
    focus     = ["backend APIs", "applied ML", "data pipelines"]
    open_to   = "Junior / new grad SWE and ML engineering roles, Canada, US, or remote"
```

- I build backend services and ML systems and run them in production: three of my apps are live, one on its own domain with a public API and an MCP server on npm.
- I care about measured results: profiling a slow path, writing the test that pins the number, and shipping the fix behind CI.
- Currently an **ML intern at Sphere Global**, building a synthetic training-data pipeline and computer-vision tooling for automated vehicle damage detection.
- Off keyboard: rugby, and the Tour de Guelph 75K every year.

---

### Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)

**Data & ML**

![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Spark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Prefect](https://img.shields.io/badge/Prefect-070E10?style=flat-square&logo=prefect&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)

**Backend & Web**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)

**Infra & Data Stores**

![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

---

### Featured Projects

| Project | What it does | Stack |
| :--- | :--- | :--- |
| **[FitFileSize](https://fitfilesize.com)** <br> Live | Compresses PDFs and images (7 formats, including iPhone HEIC) to fit an upload limit or a form's exact rules, with a web app, public API, and an MCP server on npm. Async pipeline of FastAPI, Redis/RQ workers, and Server-Sent Events, self-hosted in Docker behind a Cloudflare Tunnel with deploy-on-merge. A guided search halved renders per job and took a 5 MB photo from 9.2 s to 4.2 s with byte-identical output, behind ~350 tests across three CI jobs. <br> *[Code](https://github.com/Gautamstar/fitfilesize)* | `Python` `FastAPI` `Redis` `React` `TypeScript` `Docker` `MCP` |
| **[Distill](https://github.com/Gautamstar/distill)** <br> Applied ML | Reads invoices and receipts into typed JSON with a local vision-language model (Qwen2.5-VL). Per-field confidence from self-consistency sampling routes untrusted fields to a human, lifting delivered accuracy from 80% to 97%. 175 tests and a CI gate that fails the build when a published metric moves. | <br> *[Code](https://github.com/Gautamstar/distill)* | `PyTorch` `Qwen2.5-VL` `Pydantic` `FastAPI` `Docker` |
| **[Cairn](https://d1fspum1n48e1s.cloudfront.net/)** <br> Live | Privacy-first web analytics: a Rust ingest path on ARM64 AWS Lambda with no cookies and no stored IPs. Visitor IDs are a keyed BLAKE3 hash under a daily-rotating salt. One DynamoDB write per event, 5.1 ms warm and 184 ms cold, 41 Terraform-managed resources tracking three live sites at zero steady-state cost. <br> *[Code](https://github.com/Gautamstar/cairn)* | `Rust` `AWS Lambda` `DynamoDB` `CloudFront` `Terraform` |
| **[The Almanac](https://github.com/NolanMM/Capstones_Stock_Prediction)** <br> Team capstone | Market-data pipeline on Databricks + ADF feeding an LSTM forecaster, served via Django REST to web and Flutter clients. Redesigned the storage layer for ~35% faster loads. | `Databricks` `PySpark` `Azure SQL` `PyTorch` `Django` `Flutter` |
| **[Financial Document Q&A](https://github.com/Gautamstar/rag-financial-qa)** <br> RAG | Hybrid BM25 + FAISS retrieval with reciprocal rank fusion over SEC 10-K filings, token streaming, RAGAS evaluated. | `LangChain` `FAISS` `FastAPI` `Docker` |
| **[EDA Web Service](https://eda-proj.vercel.app)** <br> Live | Upload a CSV, get type inference, quality flags, and per column charts. Bundle trimmed 5.1 MB to 1.8 MB. | `FastAPI` `React` `Supabase` `Plotly` |

---

### Open Source

- **[actualbudget/actual #8603](https://github.com/actualbudget/actual/pull/8603)** (merged): fixed a silent failure in a widely used open-source personal finance app, returning a proper error when a password change is attempted with no password method set.

---

### GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Gautamstar&show_icons=true&include_all_commits=true&count_private=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=7AA2F7&icon_color=7AA2F7" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Gautamstar&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=7AA2F7&hide=jupyter%20notebook" alt="Top languages" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Gautamstar&theme=tokyo-night&hide_border=true&bg_color=0D1117&color=7AA2F7&line=7AA2F7&point=FFFFFF&area=true" alt="Activity graph" width="98%" />

</div>

---

<div align="center">

<sub>Open to junior software and ML engineering roles. Reach me at <a href="mailto:gautamsingh2189@gmail.com">gautamsingh2189@gmail.com</a>.</sub>

</div>
