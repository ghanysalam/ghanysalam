# Ghany Salam — Data Engineer · Data Scientist

Data Engineer and Data Scientist with a background in banking analytics, specializing in building end-to-end data infrastructure and applying machine learning to real-world problems. At Bank Woori Saudara, I engineered automated pipelines that cut reporting time by 60% and slashed branch KPI deficits by 94%. Recently completed a full modern data stack: real-time CDC pipeline (Kafka + Debezium), orchestrated batch loading into Snowflake via Airflow, and dbt transformations with Star Schema & SCD Type-2. On the ML side, I've built models for mortality-risk, travel-claim prediction, bank marketing response, NLP on 1.6M tweets, and computer vision with CNN & CNN–ViT using TensorFlow/Keras and PyTorch.

[LinkedIn](https://www.linkedin.com/in/ghanysalam) · [Portfolio](https://ghanysalam.github.io/Ghany-Portfolio) · ghany.salam12@gmail.com · Jakarta, Indonesia

---

## Experience

**Data Analyst — Bank Woori Saudara (Mar 2024–Aug 2025, Jakarta)**
- Engineered a Python data pipeline combining various sources, powering a Tableau dashboard to track KPIs across 150+ branches — reducing branches with minus KPI from ~17 to 1 within 3 months (94% improvement).
- Transformed daily and weekly reporting from manual Excel processes to seamless Python + Tableau integration, improving time efficiency by 60%.
- Analyzed debtor health portfolios, generating data-driven insights that reduced outstanding claims by 17% through improved risk monitoring.
- Developed a classification model to identify debtors at high risk of loan default caused by death using Logistic Regression.
- Analyzed life insurance credit portfolios across all insurance partners to identify high-performing providers, driving 15% cost efficiency improvement for bank procurement.

---

## Selected Projects

### Data Engineering

### 1) Flights Operations Airflow Pipeline (Batch Data Engineering & Analytics)
End-to-end batch data pipeline orchestrating live flight state extraction via OpenSky Network API, utilizing modular Python scripts and containerized Airflow for automated transformation and load into Snowflake Gold-layer tables, powering an interactive Streamlit dashboard for global aviation KPI monitoring and geospatial distribution analysis.

- **Tech:** Apache Airflow, Python, Snowflake, Streamlit, PostgreSQL, Docker, Altair
- **Repo:** [Flights Operations Airflow Pipeline (Batch Data Engineering & Analytics)](https://github.com/ghanysalam/flights-ops-airflow)

### 2) Banking Modern Data Stack (Real-time & Batch Engineering)
End-to-end banking data platform featuring real-time CDC via Kafka & Debezium into MinIO, orchestrated with Airflow for incremental batch loading into Snowflake, dbt transformations supporting SCD Type-2 history tracking and Star Schema within a Medallion architecture.

- **Tech:** Apache Kafka, Debezium, Apache Airflow, MinIO, Snowflake, dbt, Docker
- **Repo:** [Banking Modern Data Stack (Real-time & Batch Engineering)](https://github.com/ghanysalam/banking-data-engineering)

### 3) NYC Taxi Data Pipeline (Analytics Engineering)
End-to-end data platform orchestrating automated ETL/ELT with Kestra and dbt for Star Schema in BigQuery, with scalable batch and real-time stream processing using Apache Spark, Kafka, and Apache Flink.

- **Tech:** Apache Spark, Kafka, Apache Flink, Kestra, dbt, BigQuery, GCP
- **Repo:** [NYC Taxi Data Pipeline (Analytics Engineering)](https://github.com/ghanysalam/data-engineering-bootcamp)

---

### Machine Learning & Data Science

### 3) Land Classification (Satellite Imagery): CNN & CNN–ViT (Keras vs PyTorch)
Built a computer vision model to classify agri vs non-agri land cover from 6,000 satellite images; benchmarked CNN vs CNN–ViT hybrid, achieving up to 99.9% accuracy and ROC-AUC 1.00.

- **Tech:** TensorFlow, PyTorch, Deep Learning (CNN), Transformers (ViT)
- **Repo:** [Land Classification (Satellite Imagery)](https://github.com/ghanysalam/Land-Classification-Satellite-Imagery-CNN-CNN-ViT-with-Keras-PyTorch)

### 4) Classify Waste Products (TensorFlow/Keras)
Waste image classifier distinguishing organic vs recyclable using transfer learning (VGG16). Achieved 87% test accuracy with macro F1-score 0.87.

- **Tech:** TensorFlow, Deep Learning (CNN)
- **Repo:** [Classify Waste Products Using Transfer Learning](https://github.com/ghanysalam/Classify-Waste-Products-Using-Transfer-Learning)

### 5) Twitter Sentiment Analysis using Machine Learning
NLP model on 1.6M labeled tweets using TF-IDF; compared SVM/LR/NB and selected Logistic Regression with ~80% accuracy for scalable, automated sentiment insights.

- **Tech:** scikit-learn, NLTK/VADER
- **Repo:** [Twitter Sentiment Analysis](https://github.com/ghanysalam/Twitter-Sentiment-Analysis-using-Machine-Learning)

### 6) Bank Marketing Campaigns — Term Deposit
Predicted customers likely to subscribe to a term deposit using demographic, behavioral, and macro features. Model improved targeting efficiency and delivered **additional savings of USD 60,358.97** vs. traditional methods.

- **Tech:** Python, scikit-learn, SQL, Tableau
- **Repo:** [Term Deposit Subscription Prediction](https://github.com/PurwadhikaDev/BetaGroup_JC_DS_OL_11_FinalProject)

### 7) Travel Insurance Analytics — Claim Prediction
Classification model to prioritize policyholders with higher claim likelihood, guiding resource allocation and marketing. Strategy driven by the model produced **~59% profit uplift**.

- **Tech:** Python (pandas, numpy, scikit-learn), Matplotlib/Seaborn
- **Repo:** [Travel Insurance Analytics: Insurance Claim Prediction](https://github.com/ghanysalam/Capstone-3-Travel-Insurance-Prediction-Claim)

### 8) Transjakarta User Behavior Analysis
Statistical analysis of rider behavior and corridor utilization for service efficiency. Recommendations reduced the busiest corridor travel time from **102 → 27 minutes** and showed potential **~400% revenue growth**.

- **Tech:** Python/R, SQL, Matplotlib/ggplot2, advanced statistics
- **Repo:** [Transjakarta Transaction Analysis](https://github.com/ghanysalam/Capstone_2-Transjakarta_Transactions_Analysis)

---

## Skills

- **Languages & Cloud:** Python (pandas, numpy, scikit-learn, Matplotlib, Seaborn), SQL (PostgreSQL, BigQuery, Snowflake, MS SQL Server), GCP, Terraform, Docker, Git
- **Data Engineering:** Apache Spark · Kafka · Apache Flink · Debezium (CDC) · Airflow · Kestra · dbt · Snowflake · BigQuery · MinIO · Star Schema · SCD Type-2 · Medallion Architecture
- **Machine Learning:** Regression, Classification, Clustering, Time Series
- **Deep Learning & CV:** CNN, CNN–ViT, Transfer Learning (TensorFlow/Keras, PyTorch)
- **NLP:** TF-IDF, BoW, Sentiment (VADER), Topic Modeling, Text Classification
- **BI & Visualization:** Tableau, Power BI, Matplotlib, Seaborn
- **Ways of Working:** clean documentation, automation of repeatable tasks, measurable experiments, and actionable storytelling

---

## Education & Certifications

- **Data Engineering Zoomcamp** — DataTalks.Club (Feb 2026–Apr 2026)
- **IBM** — AI Engineer Professional Certificate (Dec 2025–Feb 2026)
- **Purwadhika Digital Technology School** — Certificate in Data Science & Machine Learning (Score 82.97/100)
- **UPN Veteran Jakarta** — B.Sc. in Computer Science, Cum Laude (GPA 3.76/4.00)

---

## Let's Work Together

Open to full-time roles and freelance projects in data engineering, analytics, and applied ML/AI.
Reach me at **ghany.salam12@gmail.com** or DM on **LinkedIn**.
