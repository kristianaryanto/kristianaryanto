# Kristian Aryanto Wibowo

### Senior Data Engineer & Cloud Architect

Building scalable data systems and distributed query engines. Passionate about open-source, performance optimization, and modern data architecture.

📍 Jakarta, Indonesia | 📧 [a.wkristian2@gmail.com](mailto:a.wkristian2@gmail.com) | 🔗 [LinkedIn](https://linkedin.com/in/kristian-aryanto-wibowo)

---

## 🚀 Featured Projects

### 1. [🦆 Quack-Cluster: Serverless Distributed SQL Query Engine](https://github.com/kristianaryanto/quack-cluster)
A high-performance, serverless distributed SQL engine that runs analytical queries directly on object storage (S3, GCS, local files) using **DuckDB** and **Ray**—no ETL required.

- **Architecture**: Coordinator (FastAPI + SQLGlot) distributes queries to Ray worker nodes, each running an embedded DuckDB instance for parallel processing.
- **Features**: Full SQL support (aggregations, joins, window functions, CTEs), glob-based file discovery, and Apache Arrow for efficient data exchange.
- **Tech Stack**: `Python`, `Ray`, `DuckDB`, `FastAPI`, `SQLGlot`, `Docker`

---

### 2. [Modern Data Flow with Airflow + DuckDB + dbt](https://github.com/kristianaryanto/DuckDBDAGs)
A modern, high-speed ETL stack that replaces legacy tools like SSIS with **Airflow**, **DuckDB**, and **dbt** for faster, more maintainable pipelines.

- **Performance**: Processes 100,000+ rows in **6 minutes**—SSIS failed on the same workload.
- **Workflow**: Ingests from **SQL Server**, **MySQL**, and **PostgreSQL** → transforms in-memory with DuckDB via dbt → exports back to source databases.
- **Reliability**: Automated retries, dependency management, and full observability via Airflow UI.
- **Tech Stack**: `Airflow`, `DuckDB`, `dbt`, `SQL Server`, `MySQL`, `PostgreSQL`

---

### 3. [Simply Big Data: Iceberg + MinIO + Spark Lakehouse](https://github.com/kristianaryanto/SimplyBigData-IcebergMinIO-SparkLake)
A complete, containerized data lakehouse for interactive analytics on massive datasets using **Apache Iceberg**, **MinIO**, and **Spark**.

- **Storage**: Iceberg provides ACID transactions and time travel on S3-compatible storage (MinIO or AWS S3).
- **Processing**: Distributed Spark cluster with Thrift Server for SQL access via **DBeaver** or **Jupyter Notebook**.
- **Deployment**: Orchestrated via **Docker Swarm** for easy local or cloud deployment.
- **Tech Stack**: `Apache Iceberg`, `MinIO`, `Apache Spark`, `Jupyter`, `DBeaver`, `Docker Swarm`

---

### 4. [Kafka Cluster with Docker Swarm](https://github.com/kristianaryanto/confluent-multi-node-kafka)
Deployed a highly available, fault-tolerant Kafka cluster using **Docker Swarm** for orchestration.

- **Scalability**: Configured a distributed setup running across multiple nodes (Master and Worker) to ensure fault tolerance.
- **Infrastructure**: Integrated **ZooKeeper** for cluster coordination and **Schema Registry** for managing data schemas.
- **Tech Stack**: `Apache Kafka`, `Docker Swarm`, `ZooKeeper`, `Schema Registry`

---

### 5. [GPT Bot Trading for BTC on Indodax](https://github.com/kristianaryanto/GPT_BOT_TRADING_BTC_INDODAX)
An AI-powered trading bot that uses **GPT-4o-mini** to analyze market sentiment and execute automated trades on the **Indodax** exchange.

- **Functionality**: Integrates APIs to retrieve market data, analyze trends, and implement a take-profit strategy.
- **Core Logic**: Leverages AI-driven insights to optimize trading performance and decision-making.
- **Tech Stack**: `Python`, `GPT-4`, `REST APIs`

---

### 6. [🛡️ Financial Intelligence Agent: Hybrid AI for AML](https://github.com/kristianaryanto/hybrid-ai-fraud-detection)
A real-time Anti-Money Laundering (AML) system that synergizes **Isolation Forest (unsupervised ML)** with **Google Gemini LLM** for automated fraud detection and SAR generation.

- **ML Layer**: Detects statistical anomalies in transaction flows (e.g., balance discrepancies) using Isolation Forest.
- **GenAI Layer**: Gemini 1.5 Flash drafts regulator-compliant Suspicious Activity Reports (SARs) in natural language.
- **Impact**: Reduces manual review workload by ~90% while maintaining audit-ready outputs.
- **Tech Stack**: `Scikit-learn`, `FastAPI`, `Gemini API`, `React`, `Docker Compose`

---

### 7. [🚀 FinSME: Multimodal AI Agent for Financial Intelligence](https://github.com/kristianaryanto/FinSME-Multimodal-AI-Agent)
An autonomous WhatsApp-based financial assistant that converts **voice notes** and **receipt images** into structured transaction data using **Gemini 1.5 Flash**.

- **Multimodal AI**: Replaces OCR/ASR with native LLM vision & audio understanding for receipt/voice-to-JSON conversion.
- **Agentic Workflow**: Maintains conversation history to infer intent and ask clarifying questions.
- **Deployment**: Full microservices stack: Node.js (WhatsApp), FastAPI (AI logic), Google Sheets (DB).
- **Tech Stack**: `Gemini 1.5 Flash`, `whatsapp-web.js`, `FastAPI`, `Google Sheets API`, `Docker`

---

### 8. [🎓 Aksara Global: AI Career Upskilling Agent](https://github.com/kristianaryanto/aksara-ai-career-agent)
An end-to-end Generative AI platform that performs **skill gap analysis** from CVs and job descriptions, then synthesizes a personalized learning roadmap with real YouTube resources.

- **Semantic Analysis**: Uses Gemini to compare resumes against global job requirements beyond keyword matching.
- **Dynamic Curriculum**: Auto-generates weekly learning plans and populates them with live YouTube tutorials via the YouTube Data API.
- **Architecture**: React frontend + FastAPI backend + PDF parsing + strict JSON-enforced LLM outputs.
- **Tech Stack**: `Gemini 1.5`, `FastAPI`, `React`, `PyPDF2`, `YouTube Data API`, `Docker`

---

## 🛠️ Tech Stack

| Category                  | Technologies                                                                 |
|--------------------------|------------------------------------------------------------------------------|
| **Languages**            | `Python`, `SQL`, `Bash`, `JavaScript`, `TypeScript`                         |
| **Cloud Platforms**      | `GCP`, `AWS`                                                                |
| **Big Data & Processing**| `Apache Spark`, `Apache Kafka`, `Airflow`, `DuckDB`, `Ray`, `dbt`, `Prefect` |
| **Databases & Storage**  | `PostgreSQL`, `MySQL`, `SQL Server`, `BigQuery`, `Iceberg`, `MinIO`          |
| **AI/ML & GenAI**        | `Scikit-learn`, `Gemini 1.5`, `Isolation Forest`, `FastAPI`, `LLM Agents`   |
| **Orchestration**        | `Docker`, `Docker Swarm`, `Kubernetes`, `Docker Compose`                    |
| **Frontend & APIs**      | `React`, `whatsapp-web.js`, `SSE`, `REST`, `Postman`                        |

---

## 💡 About Me

I design and build data systems that are **fast**, **reliable**, and **cost-effective**. My work bridges engineering rigor with practical business impact.

- ✅ **Performance Focus**: Optimized pipelines to run **5–10x faster** than legacy systems, reducing cloud costs.
- ✅ **AI Integration**: Pioneered agentic workflows combining classical ML with LLMs for compliance, finance, and career development.
- ✅ **End-to-End Ownership**: From ingestion (Kafka, SQL sources) → transformation (dbt, Spark) → AI enrichment (Gemini) → user interface (React/WhatsApp).
- ✅ **Open Source Advocate**: All projects are MIT-licensed, containerized, and designed for easy local setup.

---

## 📊 GitHub Stats

![Kristian's GitHub Stats](https://github-readme-stats.vercel.app/api?username=kristianaryanto&show_icons=true&theme=radical)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=kristianaryanto&layout=compact&theme=radical)
