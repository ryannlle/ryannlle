# Hi 👋 I'm Ryan Le

## 🧑‍💻 About Me

I'm a Management Information Systems major with a Computer Science minor at San Diego State University, graduating May 2027. My focus is machine learning engineering — building models and the data pipelines that actually serve them in production, with an emphasis on correctness, performance, and reproducibility.

Currently Lab Coordinator at the **AI4Business Research Lab** (SDSU Research Foundation) and a Teaching Assistant for MIS 515 (Programming for Data-Driven Applications). Previously an **Applied Machine Learning Intern at Realty Income** (Summer 2026).

🌐 [ryanle.vercel.app](https://ryanle.vercel.app)

---

## 🚀 Current Work

- **Failures at the Seam** *(AI4Business Research Lab)* – Co-authored socio-technical survey of failure modes in LLM-generated code, submitted to HICSS. I wrote Section 5, Technical Consequences, synthesizing peer-reviewed literature on bugs, API misuse, security weaknesses, licensing risk, performance degradation, and slopsquatting (package hallucination as a supply-chain attack vector).

---

## 📌 Recent Projects

- **Market Sentiment Analysis** *(Realty Income, Jun–Aug 2026)* – Scoring pipeline on Azure Databricks that grades net-lease tenants and properties 0–100 on business and location health, pulling from SEC EDGAR filings, news RSS, FRED, Census ACS, and yfinance. Batched FinBERT inference, MLflow-tracked runs, and a Pydantic-validated YAML config so weights and thresholds are tunable without code changes. Trade-area scoring uses EPSG:5070 equal-area buffers via Databricks Spatial SQL with population-weighted tract economics and an explicit insufficient-data state instead of silent estimation. Cut end-to-end runtime 21× (848s → ~40s) by tracing a `lpad()` call that was silently disabling Parquet predicate pushdown across a 44 GB store, then restoring pushdown with column pruning and a session-cached index — outputs verified field-by-field against the pre-fix baseline.

- **Malicious URL Detection** – MLP feed-forward neural network for 4-class malicious URL classification, achieving 0.91 weighted F1 (0.92 accuracy) on 128,224 URLs. Built the full preprocessing and feature-engineering pipeline (Shannon entropy, URL/domain/path length metrics, digit and special-character ratios) used as the technical foundation across all team models, and benchmarked the MLP against KNN and Random Forest baselines.

---

## 💻 Tech Stack

### **Languages**
- Python
- Java
- C++
- SQL
- HTML/CSS
- DAX

### **Machine Learning & AI**
- PyTorch
- scikit-learn
- Hugging Face Transformers (FinBERT)
- MLflow
- Pandas
- NumPy
- SARIMAX
- YOLOv8

### **Data & Analytics**
- Azure Databricks
- PySpark / Spark SQL
- Parquet
- PostgreSQL
- SQLite
- Google Cloud / BigQuery
- Microsoft Fabric
- Power BI
- Matplotlib
- Seaborn

### **Backend & Web Development**
- Django
- Flask
- Pydantic
- REST API Design

### **Version Control & Tools**
- Git
- GitHub
- Azure DevOps
- VS Code

---

## Thanks for Visiting!
