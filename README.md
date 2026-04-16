# [Kiryl Liavonau](https://linkedin.com/in/kiryl-l-a6a2531b9)
**Backend Developer, 5+ years experience**

kliavonau@gmail.com | [GitHub](https://github.com/thegridless) | [LinkedIn](https://linkedin.com/in/kiryl-l-a6a2531b9) | +375 (25) 508-5738 | **GMT+3**

---

### ABOUT
Backend Developer with over 5 years of experience building high-load, scalable systems and microservice architectures. Expert in Python (3.6–3.13) and modern frameworks (FastAPI, Django 1.7–6.0). Proven track record in full-cycle development: from system design (CQRS, Event-driven) to automated CI/CD pipelines and production monitoring.

Passionate about performance optimization and code quality, utilizing AI-driven development (Cursor, Claude 3.5 Sonnet) and modern tooling (`uv`, `ruff`, `bandit`) to boost productivity. While specialized in backend, I possess strong frontend expertise (Vue 3/Nuxt, React) and can autonomously deliver end-to-end features. Experienced in leading small teams and mentoring developers.

---

### SKILLS
**Backend:** Python (3.6–3.13), Django (1.7–6.0), FastAPI, SQLAlchemy, AsyncIO, aiokafka, Pydantic, Jinja2, uv, SMTP.
**Data & AI:** Kafka, Qdrant (RAG/Embeddings), ClickHouse, PostgreSQL (+PostGIS), Redis Stack, PySpark, Pandas.
**Infrastructure:** Docker, Kubernetes (AKS), Traefik, Nginx, Azure Blob Storage, Jenkins, GitLab CI/CD, Slack, Zulip.
**Monitoring & QA:** Grafana, Prometheus, ELK Stack, Sentry, Elastic APM, PyTest (Mocking/Integration), ruff, bandit.
**Architecture:** Microservices, CQRS, Event-driven Architecture, Monorepo, Custom SDK/Library Development, REST, WebSockets.

---

### EXPERIENCE

**ALUSOFT** — **Backend Developer** (Full-stack context)  
*Jun 2024 – Present*

*   **Manager Portal (High-load Service Hub):**
    *   Built asynchronous SAP and AService clients with parallel execution, **cutting response times by 40–60%** for multi-source requests.
    *   Developed a **custom internal SDK** for Pydantic validation and camelCase/snake_case conversion, **reducing boilerplate code by ~30%** across services.
    *   Designed a centralized **Messaging Service** with templates and **SMTP/IMAP** delivery status tracking, processing notifications via **Apache Pulsar** with automated retries.
    *   Implemented a flexible **API Gateway Router** supporting sequential/parallel HTTP execution based on JSON configurations and Redis step caching.
    *   Configured comprehensive observability with **Prometheus, Grafana, and ELK**, integrating **Elastic APM** to reduce MTTD (Mean Time to Detect) by identifying performance bottlenecks in real-time.
    *   **Technologies:** Python 3.13, Django 6.0, FastAPI, PostgreSQL, ClickHouse, Redis, Pulsar, Docker, K8s, Prometheus, Grafana, ELK, Elastic APM.

**VMSTETRENIM (Social Fitness Platform)** — **Backend Architect / Lead**  
*Internal Project / Core Contributor*

*   Designed and implemented a complex **CQRS and Event-driven architecture** using **Kafka** for real-time data synchronization between microservices.
*   Developed the **Events Service** with **PostGIS**, enabling high-performance geospatial search and filtering for thousands of concurrent activities.
*   Integrated **Stripe/ЮKassa** payment gateways, handling the full transaction lifecycle and subscription management.
*   Built a **RAG-based search service** using **Qdrant** and LLM embeddings to improve partner matching accuracy.
*   Configured full observability with **Prometheus, Grafana, and ELK**, reducing incident detection time (MTTD) significantly.
*   **Technologies:** FastAPI, SQLAlchemy, aiokafka, PostGIS, Qdrant, Redis Stack, Traefik, Azure (AKS, BlobStorage).

**IBA GROUP** — **Full-stack Developer**  
*Sep 2021 – Jun 2024*

*   **Datalake (Azure Cloud):**
    *   Developed ETL pipelines for massive data extraction and loading into **Azure Cloud** using **PySpark**.
    *   Built a specialized UI for data scientists to execute SQL and PySpark queries directly on the cluster.
*   **Performance Optimization:**
    *   Refactored the "Deal Monitor" service, achieving **67% faster response times** and **323% higher throughput** under peak load.
    *   Migrated legacy "Client Portal" from Python 2.7 to 3.13, resulting in **20–40% faster processing** and **15–30% lower memory usage**.
*   **Technologies:** Python, Azure, React, Pandas, GitLab CI/CD, Docker, Locust (Load Testing).

---

### EDUCATION
**Belarusian State University of Informatics and Radioelectronics (BSUIR)**  
*Bachelor of Computer Science*  
*Big Data Course (IBA Group Certification)*

---

### PERSONAL PROJECTS
*   **Investment/Expense Tracking Bots:** Python, pyTelegramBotAPI, Google Sheets API.
*   **Gym-bro Matcher:** High-performance scrapper and matcher using **DrissonPage** and FastAPI.
