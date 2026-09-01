# Hey, I'm Gustavo Henrique 👋

**Back-end Developer** · Building scalable systems, automating workflows & designing robust architectures

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gualmeidap)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/gualmeidap)
[![Profile Views](https://komarev.com/ghpvc/?username=gualmeidap&style=for-the-badge&color=6e7681)](https://github.com/gualmeidap)

---

## About Me

I'm a **Back-end Developer** building systems that solve real operational problems at scale. My focus is process orchestration, systems integration, and APIs that are both performant and maintainable. I work close to infrastructure — from containerized deployments to integrating local LLMs into production workflows — always with an eye toward clean, purposeful engineering.

Most of what I build replaces something that used to be done by hand. Document pipelines that used to be manual reconciliation. User provisioning that used to be a support ticket. That's the thread across everything below.

- 🏢 Software Developer at **Universidade Brasil**, building internal platforms for academic, financial and IT operations
- 🎓 B.Sc. in Computer Science at **UNICID** — expected graduation Dec 2026
- 🔭 Currently working on identity and access automation across two Active Directory domains
- 🧠 Exploring local AI inference with **Ollama** for private, production-ready LLM integration
- 🐳 Strong believer in containerized, reproducible environments

---

## 🛠 Tech Stack

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

### Frameworks & Libraries

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Tesseract OCR](https://img.shields.io/badge/Tesseract_OCR-5C3EE8?style=flat-square&logo=tesseract&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

### Data

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

### Infrastructure & Tools

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

### Practices

`REST APIs` · `Microservices` · `JWT` · `Clean Code` · `SOLID` · `Layered Architecture` · `Async Processing`

---

## 🚀 Featured Projects

### 🧾 Tax Document Automation & Intelligent Extraction

> End-to-end back-end system that automates tax document workflows. The extraction engine reads, decrypts and reconciles invoices and payment slips from dozens of suppliers, backed by intelligent email tracking, automated archiving to SharePoint and an interactive management dashboard. Replaced a fully manual reconciliation process and shortened the purchase approval cycle.
>
> **Engineering focus:** low-confidence extractions are routed to a human review queue instead of being guessed — wrong data never silently enters the approval flow.

[![Automação Fiscal Dashboard](https://raw.githubusercontent.com/gualmeidap/api-notas-demo/main/docs/capturas/demo-github.gif)](https://github.com/gualmeidap/api-notas-demo)

**Demo:** [Access Live System](https://api-notas-demo.onrender.com/) · **Repository:** [api-notas-demo](https://github.com/gualmeidap/api-notas-demo)

`Python` · `FastAPI` · `Tesseract OCR` · `IMAP/SMTP` · `Microsoft Graph API` · `PostgreSQL` · `Docker`

---

### 🔐 User Provisioning Integration — Portal 365 × TOTVS RM

> Integration between the institutional portal and the TOTVS RM database for user account provisioning: creation, password reset and access blocking. Replaced a workflow that depended on manually opening a ticket with the IT department, with identity validation against academic records and handling of two distinct Active Directory domains.

[![Portal TI: provisioning across Microsoft 365, the local directory and the ERP in one action, plus the automatic refusal when blocking a technician](https://raw.githubusercontent.com/gualmeidap/portal-ti-o365-demo/main/docs/capturas/portal-ti.gif)](https://github.com/gualmeidap/portal-ti-o365-demo)

**Demo:** [Access Live System](https://portal-ti-o365-demo.onrender.com/) · **Repository:** [portal-ti-o365-demo](https://github.com/gualmeidap/portal-ti-o365-demo)

`Python` · `TOTVS RM` · `Active Directory / LDAP` · `SQL Server` · `REST APIs`

---

### ✒️ Electronic Signature Portal — DocuSeal × Active Directory

> Internal corporate portal that runs electronic signature workflows for HR, Finance and IT. Handles documents with any number of signers, optional strict ordering, deadlines and CC, pulling contacts straight from the institutional Active Directory. Signers never leave the platform — the DocuSeal widget opens inside the dashboard itself.
>
> **Engineering focus:** the dashboard updates itself. When a document is signed, DocuSeal fires an HMAC-SHA256 webhook at the Go back end, which pushes the change to every open screen over Server-Sent Events — no polling, and nobody reloads a page to find out whose turn it is.

**Source:** internal system — repository not public

`Go 1.24` · `React 19` · `PostgreSQL` · `Active Directory / LDAP` · `Server-Sent Events` · `Microsoft Graph API` · `Tailwind CSS`

---

### 🔑 Student Password Self-Service

> Lets a student reset their own Active Directory password without going through the registrar's office. Identity is validated as a block against academic records — student ID, national ID and date of birth — and a single-use 6-digit code then goes to the academic email address, valid for 15 minutes. The new password is checked against domain policy before the bind, and the account is unlocked in the same operation.
>
> **Engineering focus:** the response is identical whether the student ID exists or not, so the form can't be turned into an enrollment enumeration oracle. Rate limiting (3 per ID, 10 per IP every 30 minutes) is applied *before* any query reaches the ERP, so a flood never becomes database load.

**Source:** internal system — repository not public

`Python` · `Active Directory / LDAP` · `TOTVS RM` · `Microsoft Graph API`

---

### 🤝 Partnership Management System

> Internal back-end platform for information extraction, email workflow orchestration and auditing, combining OCR with locally hosted generative AI. Replaced entirely manual, spreadsheet-based workflows, centralizing partnership tracking, contract management and operational reporting into a single auditable system with role-based access.
>
> **Engineering focus:** production practices for AI agents — traceability, output quality monitoring, hallucination mitigation and explicit guardrails. Digital PDFs are parsed directly; only pages that come back empty fall through to OCR, so the expensive path runs when it is actually needed.

**Repository:** [api-convenios](https://github.com/gualmeidap/api-convenios)

`Python` · `Flask` · `PostgreSQL` · `Tesseract OCR` · `Ollama` · `SQLAlchemy`

---

## 🔨 Currently Building

### 🛰 Sentinela — Availability & Business Event Monitoring

> Dashboard that answers two questions instead of one: whether each production system is responding, and what it actually did — how many password resets succeeded today, how many failed, and why. Uptime tooling covers the first question well, but none of it knows what a "password reset" is; that meaning only exists inside the monitored systems. A green panel and a stuck user coexist without contradicting each other, and that gap is what this covers.
>
> **Design constraint:** no personal data ever enters Sentinela — not masked on display, it never leaves the source system. Event types and failure reasons come from a closed vocabulary instead of raw log messages: raw messages eventually smuggle in a username, and they break grouping. "3 failures, all from the same unavailable dependency" is the useful answer; "3 failures" is not.

**Status:** early development — API skeleton deployed, collector and web panel not started yet · **Repository:** [sentinela](https://github.com/gualmeidap/sentinela)

`Java 21` · `Spring Boot` · `AWS Lambda` · `DynamoDB` · `EventBridge` · `S3 + CloudFront`

---

## 📊 GitHub Metrics

### Lines of Code & Languages

| ![GitHub Stats](./stats.svg) | ![Top Languages](./langs.svg) |
| --- | --- |

---

### 📈 Contribution Activity Graph

![Contribution Activity Graph](./activity.svg)

---

*"First, solve the problem. Then, write the code."* — John Johnson