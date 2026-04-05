<h1 align="center">Yousra Khallou</h1>

<p align="center">
  <strong>Data Engineering Student · ENSA Al Hoceima</strong><br/>
  Big Data · Machine Learning · Distributed Systems
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/yousra-khallou">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:khallouyoussra84@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://telecom-retention-system.vercel.app">
    <img src="https://img.shields.io/badge/Live_Demo-000000?style=flat&logo=vercel&logoColor=white"/>
  </a>
</p>

---

## About me

2nd-year Data Engineering student at the National School of Applied Sciences of Al Hoceima (Morocco), building end-to-end data systems — from distributed pipelines and real-time streaming to ML models and deployed APIs.

Currently looking for a **summer internship (PFA 2026)** in Data Engineering, Data Science, or Backend/Data.

---

## Featured projects

### TaaSim — Real-time Big Data platform for urban mobility
> *Capstone project · Advanced Big Data · ENSA Al Hoceima · 2025–2026 (in progress)*

End-to-end Kappa architecture to optimize taxi demand in Casablanca (4M inhabitants).
Map-matched 1.7M GPS trips (Porto Taxi dataset) onto the Casablanca OSM road network using PySpark UDFs and KD-Tree snapping.

**Stack:** Apache Kafka · Apache Flink · Apache Spark 3.5 · MinIO · Cassandra · Grafana · FastAPI · Docker · OSMnx · Python

```
GPS ingestion → Kafka → Flink streaming (3 jobs) → Spark ETL + MLlib forecasting → Grafana dashboard
```

[![Repo](https://img.shields.io/badge/GitHub-taasim--platform-181717?style=flat&logo=github)](https://github.com/Yousra-khallou/taasim-platform)

---

### AI Telecom Customer Retention System
> *End-to-end AI system · XGBoost · DistilBERT · Hybrid Recommendations · Deployed*

Three complementary AI models unified into one retention pipeline:
- **Churn prediction** — XGBoost pipeline on IBM Telco dataset (~7k customers, 20 features), F1 ~0.72
- **NLP sentiment analysis** — fine-tuned multilingual DistilBERT (EN + FR), accuracy ~0.89
- **Hybrid recommendation** — SVD collaborative filtering scored with churn + sentiment signals

Deployed as two FastAPI services on HuggingFace Spaces (Docker) + React dashboard on Vercel.

**Stack:** Python · scikit-learn · XGBoost · HuggingFace Transformers · FastAPI · React · Vercel · Docker

[![Repo](https://img.shields.io/badge/GitHub-AI--Telecom--Retention-181717?style=flat&logo=github)](https://github.com/Yousra-khallou/AI-Telecom-Customer-Retention-System)
[![Dashboard](https://img.shields.io/badge/Live_Demo-Vercel-000000?style=flat&logo=vercel)](https://telecom-retention-system.vercel.app)
[![API](https://img.shields.io/badge/API_Docs-HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)](https://usraai-telecom-churn-reco.hf.space/docs)

---

### Distributed Marketplace Catalog — MongoDB Sharding
> *Distributed databases · MongoDB sharded cluster · Kafka · Docker*

Distributed product catalog for a marketplace (Olist dataset) built on a MongoDB sharded cluster.
Implemented a Kafka producer/consumer pipeline to ingest and route catalog events across shards, with a Python dashboard for real-time monitoring.

**Stack:** MongoDB · Docker Compose · Apache Kafka · Python · Pandas

[![Repo](https://img.shields.io/badge/GitHub-MongoDB--Sharding-181717?style=flat&logo=github)](https://github.com/Yousra-khallou/marketplace-distributed-catalog-mongodb_sharded-)

---

## Skills

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

**Big Data & Streaming**

![Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![Flink](https://img.shields.io/badge/Apache_Flink-E6526F?style=flat&logo=apacheflink&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-C72C48?style=flat&logo=minio&logoColor=white)

**Machine Learning & AI**

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?style=flat)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)

**Databases**

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Cassandra](https://img.shields.io/badge/Cassandra-1287B1?style=flat&logo=apachecassandra&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)

**DevOps & Tools**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)

---

<p align="center">
  <em>Open to collaboration, internship opportunities, and new challenges in data engineering.</em>
</p>
