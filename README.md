# Hi, I'm Likitha 👋

### Software & Data Engineer · Sydney, Australia

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/likitha-v-9b8a55213)

I build things that run in production: APIs, data pipelines and the monitoring that tells you when they break. I hold a Master of Data Science from Macquarie University, and I like working the way real teams do: clear requirements, small pull requests, CI that blocks bad changes, and drills that test what happens when things fail.

---

## 🚀 Featured: Splunk capacity planning

Two projects that work together. SizeRight plans a customer's Splunk stack, and StackWatch checks that the plan stays right as usage changes.

| Project | What it does | Highlights |
|---|---|---|
| [**SizeRight**](https://github.com/Likithaa07/sizeright) | Go API that turns a Splunk subscription into a deployment plan (indexers, search heads, storage) with a reason for every number, plus Terraform inputs | +41% throughput from load testing · chaos drills found and fixed a real outage bug · JWT, rate limits, Redis cache · [live on Render](https://sizeright.onrender.com/healthz) |
| [**StackWatch**](https://github.com/Likithaa07/stackwatch) | Splunk app that compares each plan with real usage and alerts when a stack is undersized, oversized or silent | Detects undersized stacks in 12.1 min · 5 throttled alerts with runbooks · Kubernetes + Helm · 93% test coverage |

---
## 🧠 Master's Major Project: Graph Neural Networks for Fraud Detection

A 4-person research project at Macquarie University testing how well Graph Neural Networks (GNNs) detect fraud hidden in large networks of users, reviews and transactions. The team benchmarked 20+ graph fraud and anomaly detection models on 5 real-world datasets.

**My part:**

- **Dataset verification:** computed each dataset's statistics directly from the graph files (YelpChi, Amazon, Elliptic, T-Finance, FDCompCN), focusing on local heterophily, the share of a fraud node's neighbours that are benign. Found that **4 of the 5 datasets were about 10× more heterophilic than their recorded values** (YelpChi: 0.117 → 0.805), meaning fraud is far more camouflaged than reported, and corrected the mismatches.
- **Models:** trained and evaluated 5 models with very different approaches: **DGA-GNN** (decision-tree features), **BSL** (learning from very few labels), **TAM** (unsupervised), **GDN** (structural shift) and **ImGSL** (graph structure learning). Each was run at 4 training ratios × 5 random seeds, with AUPRC as the main metric because fraud is rare.
- **Results:** **DGA-GNN was the best of all 20 models on YelpChi, Elliptic and FDCompCN**; ImGSL and GDN were strongest on the other datasets; BSL and TAM scored lowest. No single model wins everywhere. Presented the findings with comparison tables and visualisations.

**Team repo:** [Graph-Fraud-WK](https://github.com/kavehkarimadini/Graph-Fraud-WK) · my analysis: [`metrics_scores.ipynb`](https://github.com/kavehkarimadini/Graph-Fraud-WK/blob/master/metrics_scores.ipynb)  
**Tools:** PyTorch · DGL · PyTorch Geometric · SciPy · pandas · NVIDIA GB10 (Grace Blackwell) on Vast.ai

---

## 🌿 Data science: the NSW biodiversity credit market

A two-part study of the NSW Biodiversity Offsets Scheme, built from the government's public registers.

| Project | Question | Key finding |
|---|---|---|
| [**Credit Gap Analysis**](https://github.com/Likithaa07/nsw-biodiversity-credit-gap) | Which credit types are running out, and do they cost more? | 43 of 305 credit types in demand have **zero supply** and 71 have under a year left. Credit types with none left sell for **~69% more** after controlling for year, vegetation, region and deal size. |
| [**Credit Opportunity Map**](https://github.com/Likithaa07/nsw-credit-opportunity-map) | Where could new supply come from? | Mapped 860,669 ha of remnant vegetation and ranked 132 IBRA subregions for new stewardship sites. |

**Deliverables:** Power BI dashboard · findings report · data quality report · data dictionary · policy briefing note · ANZLIC metadata


---

| Area | Tools | Where you can see it |
|---|---|---|
| **Languages** | Python · Go · SQL | All projects · SizeRight · Postgres migrations |
| **Backend & APIs** | REST APIs · PostgreSQL · Redis · JWT auth · rate limiting | SizeRight |
| **Cloud & DevOps** | Docker · Kubernetes · Helm · Terraform · GitHub Actions · Render | SizeRight · StackWatch |
| **Observability** | Splunk (SPL, dashboards, alerts, HEC) · runbooks · chaos drills | SizeRight · StackWatch |
| **Testing & quality** | Go test · pytest · k6 load testing · ruff · govulncheck · gitleaks | SizeRight · StackWatch · NSW projects |
| **Machine learning** | PyTorch · PyTorch Geometric · DGL · scikit-learn · XGBoost · CatBoost · TensorFlow / Keras · SHAP · statsmodels | GNN fraud project · NSW price model |
| **Data & visualisation** | pandas · NumPy · GeoPandas · ArcGIS REST · Power BI · Streamlit · Matplotlib | NSW projects · GNN fraud project |
| **GPU compute** | NVIDIA GB10 on Vast.ai (cloud) | GNN fraud project |

---

## 🎓 Education

**Master of Data Science**, Macquarie University, Sydney (2024 – 2026)  
**B.Tech, Computer Science**, Jawaharlal Nehru Technological University, India (2019 – 2023)
