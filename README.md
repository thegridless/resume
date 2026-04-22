# Kiryl Liavonau
**Python Backend Developer | Full-stack Developer**

kliavonau@gmail.com | [GitHub](https://github.com/thegridless) | [LinkedIn](https://www.linkedin.com/in/kiryl-liavonau/) | +375 (25) 508-5738 | GMT+3

---

### PROFESSIONAL SUMMARY
Backend Developer with over 5 years of experience building high-load, scalable systems and microservice architectures. Expert in Python (3.6–3.13) and modern frameworks (FastAPI, Django 1.7–6.0). Specialized in system design (CQRS, Event-driven) and automated CI/CD pipelines. Proven ability to autonomously deliver end-to-end features with strong frontend expertise (Vue 3/Nuxt, React) and backend expertise (FastAPI, Django).

---

### TECHNICAL SKILLS
*   **Backend:** Python (3.13), Django (6.0), FastAPI, SQLAlchemy, AsyncIO, Pydantic, Jinja2.
*   **Frontend:** JavaScript (ES6+), TypeScript, Vue.js 3, Nuxt, React, Pinia, Redux.
*   **Data & AI:** Kafka, Qdrant (RAG/Embeddings), ClickHouse, PostgreSQL, Redis Stack, PySpark, Pandas.
*   **Architecture & Patterns:** Microservices, **CQRS**, **Event Sourcing**, **Unit of Work (UoF)**, **Strategy**, **Adapter**, Event-driven Architecture, REST, WebSockets.
*   **Infrastructure & Tools:** Docker, Kubernetes (AKS), Traefik, Nginx, Azure Cloud, Jenkins, GitLab CI/CD, uv, ruff, bandit.
*   **Monitoring & QA:** Grafana, Prometheus, ELK Stack, Sentry, Elastic APM, PyTest.

---

### WORK EXPERIENCE

**ALUSOFT** — **Backend Developer**
*Jun 2024 – Present*

*   **Manager Portal (High-load Service Hub):**
    *   Applied **Strategy** and **Adapter** patterns to unify integration with 3rd-party ERP systems (SAP, AService), **cutting response times by 40–60%** via parallel execution.
    *   Designed a centralized **Messaging Service** utilizing the **Unit of Work (UoF)** pattern to ensure atomic delivery status tracking across SMTP/IMAP and Apache Pulsar.
    *   Developed a **custom internal SDK** for Pydantic validation, **reducing boilerplate code by ~30%** and unifying API contracts.
    *   Implemented a flexible **API Gateway Router** supporting sequential/parallel execution based on Redis step caching.
    *   Configured comprehensive observability with **Prometheus, Grafana, and ELK**, integrating **Elastic APM** to reduce MTTD by real-time bottleneck identification.
    *   **Technologies:** Python 3.13, Django 6.0, FastAPI, PostgreSQL, ClickHouse, Redis, Pulsar, Docker, K8s, Elastic APM.

**VMSTETRENIM (Social Fitness Platform)** — **Backend Architect / Lead**
*Jan 2023 – May 2024*

*   Designed and implemented a complex **CQRS and Event Sourcing architecture** using **Kafka** to handle maximum system load and real-time data synchronization between microservices.
*   Developed the **Events Service**, enabling high-performance geospatial search for thousands of concurrent activities.
*   Built a **RAG-based search service** using **Qdrant** and LLM embeddings to improve partner matching accuracy.
*   Configured full observability with **Prometheus and Grafana**, reducing incident detection time significantly.
*   **Technologies:** FastAPI, SQLAlchemy, aiokafka, Qdrant, Redis Stack, Traefik, Azure (AKS).

**IBA GROUP** — **Full-stack Developer**
*Sep 2021 – Jun 2024*

*   **Datalake (Azure Cloud):** Developed ETL pipelines for massive data extraction and loading using **PySpark**. Built a UI for data scientists to execute SQL/PySpark queries.
*   **Performance Optimization:** Refactored the "Deal Monitor" service, achieving **67% faster response times** and **323% higher throughput** under peak load.
*   **Migration:** Led the migration of legacy "Client Portal" from Python 2.7 to 3.13, resulting in **30% lower memory usage** and **40% faster processing**.
*   **Technologies:** Python, Azure, React, Pandas, GitLab CI/CD, Docker, Locust.

---

### EDUCATION
**Belarusian State University of Informatics and Radioelectronics (BSUIR)**
*Bachelor of Computer Science*
*Big Data Course (IBA Group Certification)*

---

### PERSONAL PROJECTS
*   **Investment Tracking Bot:** Python, Telegram API, Google Sheets API.
*   **Gym-bro Matcher:** High-performance scrapper and matcher using **DrissonPage** and FastAPI.
