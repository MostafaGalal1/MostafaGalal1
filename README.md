<h1 align="center">Mostafa Galal</h1>

<p align="center">
  <b>Software Development Engineer I @ noon</b><br>
  Backend &amp; data-intensive systems &nbsp;·&nbsp; Alexandria, Egypt
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mostafagalal1/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="mailto:mostafam.galal82@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white"></a>
  <a href="https://codeforces.com/profile/MostafaM.Galal"><img alt="Codeforces" src="https://img.shields.io/badge/Codeforces-Expert%201619-1F8ACB?style=flat-square&logo=codeforces&logoColor=white"></a>
</p>

---

### About

I build backend services for supply-chain and last-mile logistics at **noon**, the systems that move a package from a seller's warehouse to a customer's door. Python and FastAPI microservices on GCP, backed by MySQL, BigQuery, Pub/Sub and Temporal.

Most of my work lives in the unglamorous middle of a distributed system: event-driven workers, cross-database consistency, and the pipelines where the interesting engineering is what happens when one side fails halfway through. The problems I enjoy most are the ones measured in dollars and milliseconds, like cutting a query bill by 83%, or taking a dashboard from 12 seconds to sub-second.

Currently also pursuing an **MSc in Natural Language Processing** at Alexandria University, and an Expert on Codeforces.

---

### Tech Stack

| | |
|---|---|
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![SQL](https://img.shields.io/badge/SQL-5C6BC0?style=flat-square) |
| **Backend** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-6C757D?style=flat-square&logo=express&logoColor=white) ![gRPC](https://img.shields.io/badge/gRPC%20%2F%20Protobuf-3E7A8A?style=flat-square) |
| **Data & Messaging** | ![Kafka](https://img.shields.io/badge/Kafka-5A6472?style=flat-square&logo=apachekafka&logoColor=white) ![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white) ![Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white) ![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white) ![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white) ![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white) |
| **Datastores** | ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white) ![Elasticsearch](https://img.shields.io/badge/Elasticsearch-0577A6?style=flat-square&logo=elasticsearch&logoColor=white) ![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white) |
| **Cloud & DevOps** | ![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |
| **Observability** | ![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat-square&logo=opentelemetry&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) |

---

### Experience

**Software Development Engineer I** &nbsp;·&nbsp; [noon](https://www.noon.com) &nbsp;·&nbsp; <sub>Sept 2025 to Present</sub><br>
Backend services across noon's Logistics Management System: last-mile delivery, seller returns and warehouse operations.

- Cut BigQuery spend by **~\$3K/month**, reducing scanned data from ~1.8 TB to ~0.3 TB per run (**~83%**), by re-architecting the returns enrichment pipeline around a daily dimension-staging job.
- Took a first-mile operations dashboard from **~12s to sub-second** with a pre-aggregated, incrementally materialized read model fed by a background writer.
- Diagnosed and fixed cross-database race conditions and two-phase-commit deadlocks in a high-throughput system, eliminating stuck shipments in production.

**Software Engineer Intern** &nbsp;·&nbsp; Incorta &nbsp;·&nbsp; <sub>Aug 2025 to Sept 2025</sub>

- Built a Google Sheets data connector feeding Incorta via Parquet, letting analysts ingest external data.
- Rolled out backend observability standards across services using OpenTelemetry, Loki, Tempo and InfluxDB.

**Automation Engineer** &nbsp;·&nbsp; Everything to Gain <sub>(US startup)</sub> &nbsp;·&nbsp; <sub>Jul 2025 to Aug 2025</sub>

- Built an AI assistant bot with a React frontend and FastAPI backend for interactive real-time user support.
- Automated cross-platform integrations with Zapier and n8n, and designed HubSpot CRM workflows.

**Software Engineer Intern** &nbsp;·&nbsp; Applied Innovation Center (AIC-MCIT) &nbsp;·&nbsp; <sub>Aug 2024 to Sept 2024</sub>

- Cut frontend Docker build time from **14m 36s to 4m 47s (3x)** by optimizing the container and build pipeline.
- Built a multi-language translation feature streaming responses over SSE across **20+ languages**.

---

### Education

**MSc, Natural Language Processing** &nbsp;·&nbsp; <sub>Sept 2025 to Present</sub><br>
University of Alexandria, Faculty of Engineering

**BE, Computer and Systems Engineering** &nbsp;·&nbsp; <sub>Sept 2020 to June 2025</sub><br>
University of Alexandria, Faculty of Engineering. CGPA **3.85 / 4.0**, graduated **5th in class**.

---

### Selected Work

**[JobSeeker](https://github.com/MostafaGalal1/JobSeeker)**<br>
Microservice platform for semantic matching between résumés and job postings. Three services split by responsibility: résumé extraction and embedding, job-posting indexing, and vector-similarity search. Deployed on Kubernetes.<br>
<sub>`Python` · `LangChain` · `Qdrant` · `RabbitMQ` · `Docker` · `K8s` · `Terraform`</sub>

**[WeatherHub](https://github.com/MostafaGalal1/WeatherHub)**<br>
Real-time weather-station pipeline built around a **key-value store implemented from scratch** on the Bitcask model (append-only log, in-memory hash index, compaction). Kafka for ingest, Elasticsearch and Kibana for analytics, Parquet for cold storage.<br>
<sub>`Java` · `Kafka` · `Elasticsearch` · `Docker` · `Kubernetes`</sub>

**[Secpar](https://github.com/MostafaGalal1/Secpar)**<br>
CLI tool that scrapes competitive-programming submissions from Codeforces, CSES and Vjudge, then archives them to GitHub with generated indexes. Scrapes **1,500 submissions in under 8 minutes**, published on PyPI with **8,000+ installations**.<br>
<sub>`Python` · `PyPI` · `CLI`</sub>

**[claude-code-smart-router](https://github.com/MostafaGalal1/claude-code-smart-router)**<br>
Provider-agnostic LLM tier router that classifies each request with a small model and dispatches it to the cheapest model that can handle it. Measured **70-85% cost reduction** across Anthropic, Gemini, OpenAI, OpenRouter, Groq, DeepSeek and Ollama.<br>
<sub>`JavaScript` · `LLM infrastructure`</sub>

**[OLAP ETL with NiFi & Spark](https://github.com/MostafaGalal1/OLAP-ETL-with-Apache-NiFi-Spark)**<br>
Pipeline converting an OLTP relational schema into an OLAP star schema, benchmarked against TPC-H with Parquet output.<br>
<sub>`Python` · `NiFi` · `Spark` · `MySQL`</sub>

**[CSED25 Internships](https://github.com/MostafaGalal1/CSED25_Internships)** ![stars](https://img.shields.io/github/stars/MostafaGalal1/CSED25_Internships?style=flat-square&label=&color=555)<br>
Community-maintained internship index for Computer Engineering students, and the most-used thing I've published.

---

### Competitive Programming & Community

**Expert on Codeforces**, max rating **1619**. Roughly 1,200 archived solutions across Codeforces, CSES and Vjudge, auto-published by [Secpar](https://github.com/MostafaGalal1/Secpar) into [CP-Submissions](https://github.com/MostafaGalal1/CP-Submissions). Competed in the Egyptian Collegiate Programming Contest, Meta Hacker Cup and Dell Hacktrick.

Instructor with the **FOE Alexandria ICPC Community**, former **Vice-Chairman of ACM Alex SC**, and former Speaker of the FOE Student Union.

<a href="https://codeforces.com/profile/MostafaM.Galal"><img alt="Codeforces profile" src="https://img.shields.io/badge/codeforces-MostafaM.Galal-1F8ACB?style=flat-square&logo=codeforces&logoColor=white"></a>
<a href="https://github.com/MostafaGalal1/CP-Submissions"><img alt="Submissions archive" src="https://img.shields.io/badge/archive-CP--Submissions-181717?style=flat-square&logo=github&logoColor=white"></a>

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/MostafaGalal1/MostafaGalal1/output/github-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/MostafaGalal1/MostafaGalal1/output/github-snake.svg">
  <img alt="Contribution graph snake animation" src="https://raw.githubusercontent.com/MostafaGalal1/MostafaGalal1/output/github-snake.svg">
</picture>
