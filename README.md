# Matias Senia

Engineering reliable backend systems where deterministic software and AI capabilities work together.

### Backend & AI Integration Engineer

Building scalable APIs, AI-enabled applications, workflow automation, and production-ready services with **Python**, **FastAPI**, **LangGraph**, **Docker**, **PostgreSQL**, and **AWS**.

**[LinkedIn](https://linkedin.com/in/matiassenia)** · **[Email](mailto:matiasseniadev@gmail.com)** · [GitHub](https://github.com/matiassenia)

---

## ⚙️ Engineering Focus

**Backend systems:** API design, async services, authentication, validation, workflow orchestration, observability, and deployment readiness.

**AI integration:** LangGraph workflows, LLM-grounded analytics, deterministic fallbacks, tool boundaries, and retrieval-oriented system design.

---

## 🛠 Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

## 🌱 Currently Building

- AI systems with explicit safety boundaries.
- LangGraph workflows for backend orchestration.
- FastAPI services with clear contracts.
- Workflow automation for operational processes.
- LLM applications grounded in backend data.
- Retrieval-based systems and observability patterns.

---

## 🚀 Featured Projects

### [DataAnalizerPy](https://github.com/matiassenia/DataAnalizerPy)

Local-first analytics platform for restaurant operations.

**Problem:** Converts operational CSV/XLSX exports into KPIs, trends, audit records, and AI-assisted insights over backend-computed metrics.

**Architecture:** Static dashboard -> FastAPI API -> upload validation -> ETL pipeline -> SQLite analytics store -> BI engine -> optional LangGraph assistant.

**Highlights:** File safety checks, duplicate handling, deterministic AI fallback, sanitized events, synthetic demo data, CI-backed tests.

**Stack:** Python 3.13, FastAPI, SQLite, Pydantic, LangGraph, Pytest, GitHub Actions.

---

### [RIMAS](https://github.com/matiassenia/rimas)

Retail intelligence backend for inventory and marketing planning.

**Problem:** Generates planning recommendations while preserving audit trails and human approval over automated decisions.

**Architecture:** FastAPI REST API -> orchestration layer -> PostgreSQL persistence -> event audit log -> optional LangGraph mode -> MLflow-ready infrastructure.

**Highlights:** Async SQLAlchemy, REST contracts, `plan_events` auditability, Docker Compose infrastructure, persisted agent outputs.

**Stack:** Python, FastAPI, PostgreSQL, SQLAlchemy Async, Pydantic v2, Docker, MLflow, Pytest, LangGraph.

---

### [CanchealApp](https://github.com/matiassenia/canchealApp)

Football field booking platform with player and club-owner workflows.

**Problem:** Supports club discovery, slot availability, booking management, and owner workflows for fields and weekly schedules.

**Architecture:** Next.js frontend -> Express API -> Prisma ORM -> PostgreSQL, with JWT authentication and role-based authorization.

**Highlights:** Overlap protection, soft cancellation, owner/player role boundaries, seeded demo data, local Postgres through Docker Compose.

**Stack:** Node.js, Express, Prisma, PostgreSQL, Next.js, React, Tailwind CSS, Docker Compose.

---

### [Worldsys Backend Challenge](https://github.com/matiassenia/worldsys-backend-challenge-)

Streaming file-ingestion microservice for large customer datasets.

**Problem:** Processes large `.dat` files, rejects malformed rows, bulk-inserts valid clients, and keeps `/health` available during ingestion.

**Architecture:** Node.js service -> streaming reader -> validation layer -> queue/worker batching -> SQL Server bulk insert -> Dockerized runtime.

**Highlights:** Streaming IO, low-memory processing, batch inserts, database retries, progress logging, separated reader/worker flow.

**Stack:** TypeScript, Node.js, Docker, SQL Server, streaming IO, batch processing.

---

## 📌 Engineering Principles

- API-first design with clear contracts and predictable behavior.
- Clean boundaries between transport, orchestration, persistence, and domain logic.
- Production over prototypes: tests, Docker, environment isolation, and safe defaults.
- Deterministic AI systems with grounded outputs and explicit fallbacks.
- Human-in-the-loop workflows when automation affects operational decisions.
- Observability by default for debugging, traceability, and reliability.

---

## 📫 Contact

[LinkedIn](https://linkedin.com/in/matiassenia) · [Email](mailto:matiasseniadev@gmail.com) · [GitHub](https://github.com/matiassenia)
