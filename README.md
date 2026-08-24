<!--
  Profile README for github.com/angeli-sliit
  Design rule: every visual element carries a fact. No decoration that says nothing.

  TO DO before this is finished:
  1. Save the banner PNG locally and swap the src, so nothing on this page can 404.
  2. Confirm the Google Drive résumé link is shared "Anyone with the link".

  Every metric on this page is traceable to the CV. Keep it that way — if a number
  changes in one document, change it in the other the same day.
-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&height=230&color=0:0F172A,50:1E1B4B,100:0EA5E9&text=Angeli%20Wickrama%20Arachchige&fontColor=f8fafc&fontSize=40&fontAlignY=38&desc=Data%20Engineering%20%C2%B7%20ML%20Systems%20%C2%B7%20Production%20Analytics&descSize=16&descAlignY=58&stroke=0EA5E9&strokeWidth=2" alt="Angeli Wickrama Arachchige — Data Engineering, ML Systems, Production Analytics"/>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=17&duration=3000&pause=1200&color=0EA5E9&center=true&vCenter=true&width=760&lines=AI%2FML+Engineering+Intern+%40+Sri+Lanka+Telecom+PLC;28.2M+signal+readings+processed+daily+across+446%2C000+customers;Fibre+faults+detected+3-7+days+before+failure;Researching+contrastive+learning+for+antioxidant+peptides;Data+Science+%40+SLIIT+%7C+CGPA+3.40%2F4.00+%7C+Class+of+2027" alt="Typing SVG" /></a>

<br/>

<a href="https://linkedin.com/in/angeli-wickrama-arachchige-649502293"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:angeli.2003it@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://drive.google.com/file/d/1bjV6xFMKDgIKTKfttvqcwVEOaKf6mk38/view?usp=sharing"><img src="https://img.shields.io/badge/R%C3%A9sum%C3%A9-0EA5E9?style=for-the-badge&logo=readdotcv&logoColor=white" alt="Résumé"/></a>
<a href="https://web.facebook.com/LearnDSwithAngeli"><img src="https://img.shields.io/badge/Learn%20DS%20in%20Sinhala-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Learn DS in Sinhala"/></a>

</div>

---

<div align="center">

<img src="https://img.shields.io/badge/28.2M-rows%20processed%20daily-0EA5E9?style=for-the-badge&labelColor=0F172A" alt="28.2M rows processed daily"/>
<img src="https://img.shields.io/badge/446K-customers%20monitored-10B981?style=for-the-badge&labelColor=0F172A" alt="446,000 customers monitored"/>
<img src="https://img.shields.io/badge/3–7%20days-of%20early%20warning-F59E0B?style=for-the-badge&labelColor=0F172A" alt="3 to 7 days early warning"/>

</div>

---

## 🧭 About

I build data and ML systems that survive contact with production — the ETL, the warehouse, and the monitoring around a model, not just the model.

Final-year Data Science undergraduate at **SLIIT** (CGPA 3.40/4.00, graduating 2027), fresh off six months of AI/ML engineering at **Sri Lanka Telecom**, where my pipelines ran against every fibre line in the country. Currently researching contrastive learning for protein sequences under CEAI. On the side I run [**Learn DS සිංහලෙන්**](https://web.facebook.com/LearnDSwithAngeli), teaching data science in Sinhala.

> **Open to:** Data Engineering · ML Engineering · Data Science — Sri Lanka or remote.

---

## 💼 Experience

### <img src="https://img.shields.io/badge/Sri%20Lanka%20Telecom%20PLC-004B87?style=flat-square&logoColor=white" alt="SLT"/> &nbsp;AI/ML Engineering Intern &nbsp;·&nbsp; Lead Intern, FTTH Analytics &nbsp;·&nbsp; `Jan 2026 – July 2026`

**🔌 FTTH fault prediction — production, national scale**
Python/Parquet pipelines over **28.2M daily signal readings across 446,000 customers**, consolidating RX/TX signals, ACS exports and fault tickets into one validated dataset feeding three modelling workstreams. Isolation Forest + autoencoders over 55+ temporal features and a 10-rule weighted risk engine detect faults **3–7 days before failure**; cooldown logic cut daily false positives from **~378 to 70–90**, which is what made the alerts usable by field teams.

**☁️ End-to-end AWS deployment**
S3 → Lambda → SageMaker → EventBridge → CloudWatch → SES, with the feature/preprocessing layer migrated to a new `api_v2` REST schema at **zero production disruption**. Power BI dashboards for live operational monitoring.

**🛡️ Attendance anomaly detection — real-time**
26-feature pipeline (Python, AWS Lambda) into SageMaker Random Cut Forest for biometric fraud detection, held **under 10% false positives**.

**📑 Telecom fraud-AI benchmark**
30-page review of ML fraud detection across 12 operators (Vodafone, AT&T, Singtel, Dialog Axiata and others), closing with a phased adoption roadmap.

---

## 🚀 Projects

| Project | What it does | Stack |
| :--- | :--- | :--- |
| **[AirSense](https://github.com/angeli-sliit/AirSense)** | Agentic air-quality analytics — time-series forecasting plus LLM-assisted analysis over a live pipeline. | `FastAPI` `React` `MySQL` `SARIMAX/Prophet` |
| **[ArtifexAI](https://github.com/angeli-sliit/ArtifexAI)** <br/> [![demo](https://img.shields.io/badge/live-demo-F59E0B?style=flat-square)](https://huggingface.co/spaces/angeli2003/ArtifexAI) | Predicts art auction prices from 60K+ records and image-derived features. R² 0.84, SHAP for per-lot explanation. | `CatBoost` `SHAP` `Streamlit` |
| **[Global Container Shipment DWH](https://github.com/angeli-sliit/Global-Container-Shipment-DWH)** | 358K-record warehouse with SCD Type 2 dimensions and an OLAP cube behind Power BI. | `SQL Server` `SSIS` `SSAS` `Power BI` |
| **[Interview Prep RAG](https://github.com/angeli-sliit/Interview-Prep-RAG)** <br/> [![demo](https://img.shields.io/badge/live-demo-F59E0B?style=flat-square)](https://interview-prep-rag.streamlit.app) | Grounds STAR-method interview answers in the actual job description, not generic advice. | `LangChain` `ChromaDB` `HuggingFace` |
| **[Smart Campus Operations Hub](https://github.com/angeli-sliit/angeli-sliit-it3030-paf-2026-smart-campus-Y3S2-WE-180)** | Facility booking with QR check-in, OAuth2 and role-based access. | `Spring Boot` `React 19` `PostgreSQL` |
| **[AI Emotion Recognition](https://github.com/angeli-sliit/AI-Emotion-Recognition)** <br/> [![demo](https://img.shields.io/badge/live-demo-F59E0B?style=flat-square)](https://visionlense.streamlit.app/) | Real-time webcam emotion detection across 7 classes. | `TensorFlow` `OpenCV` `MobileNetV2` |

---

## 🔬 Research — AOP-ProCon

<img align="right" src="https://img.shields.io/badge/status-active-10B981?style=flat-square" alt="active"/>

Mechanism-aware, **positive-only contrastive learning** for antioxidant peptide discovery. Uses ESM-2 (650M) embeddings and leave-source-out retrieval evaluation to attack the random-negative bias that quietly inflates benchmark scores in this field.

Conducted under **PlantAOx-ReliableXAI**, Centre of Excellence in AI @ SLIIT.

---

## ⚙️ Stack

<div align="center">

<table>
<tr>
<td align="right"><b>ML&nbsp;&&nbsp;Data&nbsp;Science</b></td>
<td><img height="42" src="https://skillicons.dev/icons?i=py,sklearn,tensorflow,anaconda" alt="Python, scikit-learn, TensorFlow, Anaconda"/></td>
</tr>
<tr>
<td align="right"><b>Backend&nbsp;&&nbsp;Apps</b></td>
<td><img height="42" src="https://skillicons.dev/icons?i=fastapi,spring,java,react" alt="FastAPI, Spring Boot, Java, React"/></td>
</tr>
<tr>
<td align="right"><b>Databases</b></td>
<td><img height="42" src="https://skillicons.dev/icons?i=postgres,mysql" alt="PostgreSQL, MySQL"/></td>
</tr>
<tr>
<td align="right"><b>Cloud&nbsp;&&nbsp;Tooling</b></td>
<td><img height="42" src="https://skillicons.dev/icons?i=aws,docker,git,github" alt="AWS, Docker, Git, GitHub"/></td>
</tr>
</table>

</div>

**Data engineering & BI** — SQL Server · SSIS · SSAS · DAX · Power BI · ETL/ELT · Apache Spark · Parquet

**Modelling** — XGBoost · LightGBM · CatBoost · SARIMAX/Prophet · SHAP · Isolation Forest · Autoencoders · ESM-2

**Cloud** — AWS SageMaker · S3 · Lambda

**Certified** — AWS Certified Cloud Practitioner (2025) · Power BI Modeling & DAX, Microsoft (2025) · Data Analysis with R, Google (2025)

**Learning now** — distributed processing with Spark & Hive, data governance, MLOps.

---

## 📈 GitHub Activity

<div align="center">

<img height="170" src="https://github-readme-stats-fast.vercel.app/api?username=angeli-sliit&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub stats for angeli-sliit"/>
<img height="170" src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=angeli-sliit&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Most-used languages"/>



<img src="https://github-readme-activity-graph.vercel.app/graph?username=angeli-sliit&bg_color=1a1b27&color=38bcad&line=618dd8&point=bf91f3&area=true&hide_border=true" alt="Contribution graph"/>

</div>

---

<div align="center">

### 📬 Let's talk

[![Email](https://img.shields.io/badge/angeli.2003it@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:angeli.2003it@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/angeli-wickrama-arachchige-649502293)

Malabe, Sri Lanka · Remote-friendly

<img src="https://capsule-render.vercel.app/api?type=waving&section=footer&height=110&color=0:0F172A,50:1E1B4B,100:0EA5E9"/>

</div>
