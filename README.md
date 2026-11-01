<h1 align="center">Hi, I'm Alexey 👋</h1>
<h3 align="center">Senior Java Backend Engineer · Event-Driven Microservices · Kafka · Camunda BPM</h3>

<p align="center">
  <a href="mailto:jvm2go@gmail.com"><img src="https://img.shields.io/badge/Email-jvm2go%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://t.me/jvm2go"><img src="https://img.shields.io/badge/Telegram-@jvm2go-26A5E4?style=flat&logo=telegram&logoColor=white" alt="Telegram"/></a>
  <a href="https://www.linkedin.com/in/jvm2go"><img src="https://img.shields.io/badge/LinkedIn-Alexey%20Belyaev-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <img src="https://img.shields.io/badge/Location-Montenegro%20(UTC+1)-555?style=flat" alt="Location"/>
  <img src="https://img.shields.io/badge/Open%20to-Remote%20%7C%20B2B%20%7C%20EU%20relocation-2ea44f?style=flat" alt="Open to work"/>
</p>

---

### About me

Java backend engineer with **6+ years** of commercial experience on the JVM. I build and run event-driven microservice systems in production: asynchronous integrations via **Apache Kafka**, business-process orchestration with **Camunda BPM 7 (BPMN 2.0)**, and services on **Spring Boot + PostgreSQL**.

For the past 2+ years I've been working on an enterprise marketing automation platform for a top-3 federal grocery retailer: **10+ Spring Boot microservices, 20+ Kafka topics, a 14-stage BPMN campaign lifecycle and an audience of millions of loyalty customers**. Besides feature work, I investigate and fix production incidents: consistency gaps between PostgreSQL and Kafka, race conditions, configuration drift.

Currently expanding into **Go**.

### 🛠 Tech stack

**Languages**
![Java](https://img.shields.io/badge/Java%2017+-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat&logo=postgresql&logoColor=white)
![Go](https://img.shields.io/badge/Go%20(learning)-00ADD8?style=flat&logo=go&logoColor=white)

**Frameworks**
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat&logo=springsecurity&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate%20%2F%20JPA-59666C?style=flat&logo=hibernate&logoColor=white)
![Camunda](https://img.shields.io/badge/Camunda%20BPM%207-FC5D0D?style=flat&logo=camunda&logoColor=white)

**Messaging & data**
![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Liquibase](https://img.shields.io/badge/Liquibase-2962FF?style=flat&logo=liquibase&logoColor=white)

**Infrastructure & observability**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab%20CI-FC6D26?style=flat&logo=gitlab&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![Jaeger](https://img.shields.io/badge/Jaeger-66CFE3?style=flat&logo=jaeger&logoColor=black)

**Testing & build**
![JUnit 5](https://img.shields.io/badge/JUnit%205-25A162?style=flat&logo=junit5&logoColor=white)
![Mockito](https://img.shields.io/badge/Mockito-78A641?style=flat)
![Testcontainers](https://img.shields.io/badge/Testcontainers-291A3F?style=flat)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat&logo=gradle&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat&logo=apachemaven&logoColor=white)

### 💼 Experience

**Senior Java Backend Engineer** — IQ Group · *Feb 2024 – present*
Marketing automation platform for a top-3 federal grocery retailer (SMS, Push, Email, Viber campaigns).
- Own the core orchestration microservice (Java 17, Spring Boot); implemented a 14-stage BPMN 2.0 process in Camunda BPM 7 covering the full campaign lifecycle.
- Fixed a premature state transition in a Kafka integration: status is now updated on the downstream acknowledgement instead of on broker publish, removing a whole class of "DB says success, downstream never processed" incidents.
- Found a database lock timeout misconfigured to 15 hours instead of minutes; fixed it and added Grafana metrics on lock-hold duration.
- Built fault-tolerant Kafka integrations: idempotent producer, `acks=all`, SCRAM auth, retries and DLQ across 20+ topics.
- Set up observability: tracing in Jaeger, metrics and alerts in Prometheus + Grafana (Micrometer), structured logging.

**Java Developer** — telecom BSS billing system · *Oct 2021 – Jan 2024*
Billing microservices for a telecom operator's BSS platform.

**Java Developer** — CRM for a pharmacy chain · *Feb 2020 – Oct 2021*

### 🎯 What I'm looking for

Senior backend roles with architectural ownership: **fully remote / B2B contract**, or relocation within the EU.

---

<p align="center"><i>JVM expertise, ready to go.</i></p>
