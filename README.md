<img src="assets/hero.png" alt="Built with intent. Checked with care. Editorial banner with Ajmir Aribam's portrait on a deep green background." width="100%" />

# Md Ajmir Aribam

**Software engineer · Backend systems · Applied AI exploration**

I build across Python APIs, React interfaces, and the data models behind them. My focus is dependable product behaviour: a document finding tied to its source, an invoice transition checked by the API, a failed request that leaves a useful explanation.

Based in **Imphal, India** · Pursuing an **MCA at Sharda University, 2025–2027**.

[Portfolio](https://ajmiraribam.me/) · [Résumé](https://ajmiraribam.me/resume) · [LinkedIn](https://linkedin.com/in/ajmir-aribam/) · [Email](mailto:arajmir7@gmail.com)

## Selected engineering

### 01 / Azaeron Verity

**Document intelligence · In development · Not production ready**

A review workspace that keeps document findings attached to the version and source behind them. The implementation combines immutable revisions, tenant-scoped similarity retrieval, asynchronous analysis, and human review. A Next.js interface calls FastAPI; PostgreSQL holds versioned records, Redis/Celery handles jobs, and MinIO stores documents.

Production model approval and detector calibration remain open; no detection-accuracy claim is made.

[Repository](https://github.com/arajmir7/Azaeron-Verity) · [Architecture](https://github.com/arajmir7/Azaeron-Verity/blob/main/ARCHITECTURE.md) · [Case study](https://ajmiraribam.me/work/azaeron-verity)

### 02 / SCMIRN

**Civic-service routing · Prototype · Not production ready**

A prototype for helping people find a relevant civic-service route. React/TypeScript screens connect to a Flask API with versioned routing rules, consent checks, idempotent requests, and source-verified service handoffs. SQLAlchemy models support local SQLite development and PostgreSQL isolation checks. Routing is deterministic; it does not file requests with government agencies.

[Repository](https://github.com/arajmir7/SCMIRN) · [Routing implementation](https://github.com/arajmir7/SCMIRN/tree/main/src/backend/app/source_routing)

### 03 / Personal portfolio

**Full-stack web application · Public site**

A portfolio with a contact workflow behind the interface: Next.js forwards requests to a private FastAPI service, PostgreSQL stores inquiries and an email outbox, and Resend handles delivery. The repository includes API tests, browser accessibility checks, and migration tooling.

**Next.js · TypeScript · FastAPI · PostgreSQL · Vercel**

[Repository](https://github.com/arajmir7/ajmir-aribam-portfolio) · [Visit the site](https://ajmiraribam.me/)

**Also in my product work — [Azaeron Invoice](https://ajmiraribam.me/work/azaeron).** A React/TypeScript merchant workspace backed by Express and MongoDB. My work includes invoice lifecycle rules, server-side permissions, and audit records. Source is private; the public case study describes the implementation and the limits of verified payment workflows.

## Engineering approach

> Make the state explicit. Keep the evidence close. Verify the change.

Banking and digital public-service work shaped my attention to traceable records and clear outcomes. In software, that means enforcing rules at the API boundary, preserving data ownership, and testing consequential failure paths.

[More on my approach](https://ajmiraribam.me/engineering)

## Working toolkit

**Languages** — Python, TypeScript, JavaScript, SQL<br />
**Backend** — FastAPI, Flask, Node.js, Express, REST APIs<br />
**Frontend** — React, Next.js, Vite<br />
**Data & jobs** — PostgreSQL, SQLAlchemy, MongoDB, Redis, Celery<br />
**Delivery & tools** — Git, Docker, GitHub Actions, Vercel<br />
**Verification** — pytest, Playwright, Vitest, Ruff, axe-core

## AI & experimentation

I'm exploring document retrieval, model evaluation, and uncertainty in AI-assisted review. Verity's [retrieval pipeline](https://github.com/arajmir7/Azaeron-Verity/blob/main/backend/app/modules/similarity/service.py) and [calibration layer](https://github.com/arajmir7/Azaeron-Verity/blob/main/backend/app/modules/detection/intelligence/calibration.py) make those interests inspectable. PyTorch and sentence-transformers are optional experimental dependencies, separate from the production runtime.

---

[Explore more work](https://ajmiraribam.me/work) · [Recent repository activity](https://github.com/arajmir7?tab=repositories&sort=updated) · [Start a conversation](mailto:arajmir7@gmail.com)
