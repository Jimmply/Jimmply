# Dmitri Shurkhai — Manufacturing Data Scientist

**IIoT · Predictive Maintenance · LLM Pipelines · Aerospace Manufacturing**

4+ years building production ML and LLM systems on industrial sensor data (0.5–1 TB scale) across laser cutting, welding, CNC milling, and additive manufacturing. Reduced unplanned equipment downtime 10–15% at Laseronics LLC — an AS9100-certified, ITAR-registered precision laser shop serving aerospace OEMs and space systems integrators.

---

## Education & Certifications

| | |
|---|---|
| **M.S. Data Science** | UCLA (in progress) |
| **Data Science Certificate** | UCLA Extension — 2026 |
| **M.S. Engineering (Microelectronics)** | Moscow Institute of Electronics and Mathematics |

---

## Featured Projects

### Predictive Maintenance & Process ML

| Project | What it does | Stack |
|---|---|---|
| [**cnc-tool-wear-predictor**](https://github.com/Jimmply/cnc-tool-wear-predictor) | Wear state (Fresh/Worn/Critical) + RUL prediction from 6 sensor channels — 96.8% accuracy, ~18-cut MAE | XGBoost · Scikit-learn · Streamlit |
| [**weld-quality-classifier**](https://github.com/Jimmply/weld-quality-classifier) | 5-class laser weld quality prediction with SHAP waterfall — explains which process parameter caused each defect | XGBoost · SHAP · Streamlit |
| [**additive-process-monitor**](https://github.com/Jimmply/additive-process-monitor) | Layer-by-layer FDM printer failure detection (Clog/Warping/Stringing/Delamination) — ~90% accuracy, health score per layer | XGBoost · Scikit-learn · Streamlit |
| [**anomaly-detection-dashboard**](https://github.com/Jimmply/anomaly-detection-dashboard) | Real-time industrial sensor anomaly detection — 4 algorithms (Z-score, IQR, Isolation Forest, DBSCAN), pluggable PyOD interface | Scikit-learn · PyOD · Streamlit |

### LSR Welding / Laseronics — Domain-Specific Systems

| Project | What it does | Stack |
|---|---|---|
| [**laser-parameter-optimizer**](https://github.com/Jimmply/laser-parameter-optimizer) | Recommends Nd:YAG / LASAG SLS 200 parameters for 7 aerospace alloys (Ti-6Al-4V, Inconel 625, Hastelloy…). scipy + XGBoost surrogate optimization | XGBoost · SciPy · Streamlit |
| [**weld-signal-classifier**](https://github.com/Jimmply/weld-signal-classifier) | Real-time defect classification from 10 kHz photodiode + acoustic emission signals — Spatter, Porosity, Cracking, Lack of Fusion | XGBoost · NumPy · Streamlit |
| [**as9100-quality-tracker**](https://github.com/Jimmply/as9100-quality-tracker) | AS9100 Rev D shop floor dashboard — FPY, OTD, NCR analysis, material cert traceability for aerospace laser operations | Pandas · Plotly · Streamlit |

### LLM & RAG Systems

| Project | What it does | Stack |
|---|---|---|
| [**manufacturing-log-analyzer**](https://github.com/Jimmply/manufacturing-log-analyzer) | Provider-agnostic LLM pipeline classifying root causes across 6 failure modes in unstructured machine logs | LangChain · Gemini/Claude/OpenAI · Streamlit |
| [**rag-manufacturing-qa**](https://github.com/Jimmply/rag-manufacturing-qa) | RAG system for querying manufacturing SOPs and maintenance docs — semantic search + LLM generation with source citation | LangChain · ChromaDB · Streamlit |

---

## Tech Stack

**ML & Modeling**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-FF6B6B?style=flat)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white)

**IIoT & Manufacturing Domain**

![Predictive Maintenance](https://img.shields.io/badge/Predictive_Maintenance-2C3E50?style=flat)
![RUL Estimation](https://img.shields.io/badge/RUL_Estimation-2C3E50?style=flat)
![Anomaly Detection](https://img.shields.io/badge/Anomaly_Detection-2C3E50?style=flat)
![Time Series](https://img.shields.io/badge/Time--Series-2C3E50?style=flat)
![AS9100](https://img.shields.io/badge/AS9100D-blue?style=flat)

**LLMs & GenAI**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat)
![Anthropic](https://img.shields.io/badge/Anthropic_Claude-191919?style=flat)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-6C3483?style=flat)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=flat)

**Data Engineering & Infra**

![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)

---

## Contact

etozhejimmy@gmail.com &nbsp;·&nbsp; 💼 [LinkedIn](https://linkedin.com/in/etozhejimmy) &nbsp;·&nbsp; 📊 [Kaggle](https://kaggle.com/jimmysh) &nbsp;·&nbsp; 📍 Northridge, CA — open to Manufacturing Data Scientist roles
