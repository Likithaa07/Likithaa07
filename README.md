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

## 🧠 Research: Graph Neural Networks for fraud detection

**[Graph-Fraud-WK](https://github.com/kavehkarimadini/Graph-Fraud-WK)**: my Master's group project. We extended an open-source graph fraud-detection toolbox into a benchmark of ~20 GNN models across 5 real fraud datasets and 4 label ratios. My focus was graph-structure (heterophily) analysis. A research paper is in preparation.

---

## 🌿 Data science: the NSW biodiversity credit market

A three-part study of the NSW Biodiversity Offsets Scheme, built from the government's public registers.

| Project | Question | Key finding |
|---|---|---|
| [**Credit Gap Analysis**](https://github.com/Likithaa07/nsw-biodiversity-credit-gap) | Which credit types are running out, and do they cost more? | 43 of 305 credit types in demand have **zero supply** and 71 have under a year left. Credit types with none left sell for **~69% more** after controlling for year, vegetation, region and deal size. |
| [**What Drives Credit Prices?**](https://github.com/Likithaa07/bos-credit-prices) | Does rising demand push prices up? | Location and vegetation type explain most price variation (adj. R² 0.71, 1,284 sales). **Recent demand pressure is not priced in**: the effect is tiny and flips sign across 7 checks. |
| [**Credit Opportunity Map**](https://github.com/Likithaa07/nsw-credit-opportunity-map) | Where could new supply come from? | Mapped 860,669 ha of remnant vegetation and ranked 132 IBRA subregions for new stewardship sites. |

**Deliverables:** Power BI dashboard · findings report · data quality report · data dictionary · policy briefing note · ANZLIC metadata

---

## 📊 More projects

- [**Real-Time Fraud Detection API**](https://github.com/Likithaa07/Real-Time-Financial-Fraud-Detection-API): CatBoost/XGBoost pipeline with SMOTE, drift detection and a Flask REST API
- [**Energy Forecasting & Anomaly Detection**](https://github.com/Likithaa07/LSTM-Based-Energy-Consumption-Forecasting-and-Anomaly-Detection): multivariate LSTM on PJM power grid data
- [**Causal Impact on Retail Sales**](https://github.com/Likithaa07/Causal-Impact-Retail-Sales): measuring the true effect of marketing campaigns with DoWhy

---

## 🛠️ Tech stack

**Languages:** Python · Go · SQL  
**Backend & data:** REST APIs · PostgreSQL · Redis · pandas · NumPy  
**Observability & cloud:** Splunk (SPL, dashboards, alerts, HEC) · Docker · Kubernetes · Helm · Terraform · GitHub Actions  
**Machine learning:** scikit-learn · PyTorch · TensorFlow / Keras · XGBoost · CatBoost · statsmodels  
**Spatial & visualisation:** GeoPandas · ArcGIS REST · Power BI · Matplotlib

---

## 🎓 Education

**Master of Data Science**, Macquarie University, Sydney (2024 – 2026)  
**B.Tech, Computer Science**, Jawaharlal Nehru Technological University, India (2019 – 2023)
