# Dmitry Shurkhai

**Manufacturing Data Scientist** — IIoT · Predictive Quality · LLM Pipelines · Aerospace

4+ years building ML and LLM systems on industrial sensor data at **Laseronics LLC** (AS9100 / ITAR aerospace laser shop). M.S. Data Science at UCLA, in progress.

## Flagship projects

### 🔧 [manufacturing-log-analyzer](https://github.com/Jimmply/manufacturing-log-analyzer)
Multi-provider LLM diagnostics pipeline (Claude · Gemini · OpenAI · Ollama) for laser-welding machine logs. Anomaly detection → failure-window extraction → LLM root-cause classification → maintenance report. CLI + Streamlit dashboard. ![CI](https://github.com/Jimmply/manufacturing-log-analyzer/actions/workflows/ci.yml/badge.svg)

### 📊 [bosch-production-fault-predictor](https://github.com/Jimmply/bosch-production-fault-predictor)
Survival analysis + station-attribution SHAP on the full **14 GB · 1.18M-part** Bosch dataset. Five documented experiments (Optuna tuning, time-aware CV, drift diagnostic, windowed retraining, drift-aware features) — honest negative results included. Reveals that stratified-k-fold was leaking ~0.30 AUC and that the drift is in **P(y\|x)**, not P(x). ![CI](https://github.com/Jimmply/bosch-production-fault-predictor/actions/workflows/ci.yml/badge.svg)

### ⚙️ [cnc-calibrator](https://github.com/Jimmply/cnc-calibrator)
4-element GRBL calibration wizard with closed-loop encoder verification, tolerance-based retry, dry-run G-code preview, and a built-in simulator. 24 tests on three Python versions. ![CI](https://github.com/Jimmply/cnc-calibrator/actions/workflows/ci.yml/badge.svg)

## Other repos worth a look

| Project | What it does |
|---|---|
| [weld-quality-classifier](https://github.com/Jimmply/weld-quality-classifier) | 5-class laser weld quality classifier with SHAP + Streamlit process-window dashboard |
| [weld-signal-classifier](https://github.com/Jimmply/weld-signal-classifier) | Real-time defect detection from 10 kHz photodiode + acoustic emission signals, ~93% accuracy |
| [cnc-tool-wear-predictor](https://github.com/Jimmply/cnc-tool-wear-predictor) | Tool wear-state classifier + RUL regressor — 96.8% accuracy, ~18-cut MAE |
| [anomaly-detection-dashboard](https://github.com/Jimmply/anomaly-detection-dashboard) | Multi-algorithm industrial sensor anomaly detection (Z-score, IQR, Isolation Forest, DBSCAN) |
| [as9100-quality-tracker](https://github.com/Jimmply/as9100-quality-tracker) | AS9100 shop-floor dashboard — FPY, OTD, NCR traceability, modeled on real aerospace laser operations |
| [laser-parameter-optimizer](https://github.com/Jimmply/laser-parameter-optimizer) | XGBoost surrogate + scipy optimization for Nd:YAG weld parameters across 7 aerospace alloys |
| [rag-manufacturing-qa](https://github.com/Jimmply/rag-manufacturing-qa) | RAG over manufacturing SOPs and maintenance docs (LangChain + ChromaDB) |

## Stack

Python · XGBoost · scikit-learn · PyTorch · SHAP · LangChain · ChromaDB · Streamlit · pandas · pyarrow · SQL · Spark · Airflow · Docker · AWS

## Education

M.S. Data Science, **UCLA** (in progress, 2027) · Data Science Certificate, UCLA Extension (2026) · M.S. Engineering (Microelectronics), MIEM

## Contact

[etozhejimmy@gmail.com](mailto:etozhejimmy@gmail.com) · [LinkedIn](https://linkedin.com/in/etozhejimmy) · [Kaggle](https://kaggle.com/jimmysh) · Northridge, CA
