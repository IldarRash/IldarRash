<!--
=============================================================================
ATS-FRIENDLY RESUME CONTENT — paste into Enhancv, then export PDF and overwrite
IldarShayakhmetovResume.pdf at the repo root (referenced by index.md).

HOW TO USE (Enhancv export guidance):
- Pick a SINGLE-COLUMN template. The current PDF uses a two-column template,
  which is the root ATS failure — in parse order the sidebar text splices into
  the middle of the job bullets and gets scrambled.
- Keep the standard section headings exactly as below: Summary, Experience,
  Skills, Education, Certifications, Projects — these are the ones ATS recognize.
- Let the template's default bullet render. Do NOT use the icon/symbol bullets;
  in the old PDF those decoded as "?" garbage.
- Remove the "Powered by enhancv" watermark on export if possible.
- Keep to 1–2 pages. Export as PDF.

This file is the canonical, version-controlled source of the resume text and is
kept in sync with index.md.
=============================================================================
-->

# Ildar Shayakhmetov

**Senior Backend & AI-Systems Engineer | High-Load Fintech**

il.sach@yandex.ru · +381 62 975 4956 · Belgrade, Serbia
linkedin.com/in/ildar-shayakhmetov-8471ab164 · github.com/IldarRash · ildarrash.github.io/IldarRash

---

## Summary

Senior Backend & AI-Systems Engineer with 6+ years designing high-load, distributed backend systems. Expert in Java, Kotlin, and Scala with reactive programming (Project Reactor, Akka Streams) and deep fintech experience — payments, money movement, and PCI-DSS-compliant services. Also architects event-driven AI platforms in Rust and Python (algorithmic trading, AI health coaching). Track record of leading projects, optimizing performance, and keeping systems stable under load.

---

## Key Achievements

- Engineered a real-time streaming platform processing **15M+ messages/sec** from Kafka (Java + Akka Streams).
- Reduced memory footprint and CPU time by **80%** via a GraalVM native-image migration, cutting cloud spend by **~EUR 20k/month**.
- Delivered **PCI-DSS-compliant** payment services in production (Kotlin, Project Reactor).
- Architected an event-driven algorithmic-trading platform with an **architecturally unbypassable risk engine** (Rust + Python + Kafka).

---

## Experience

### Software Developer — Paysend
Belgrade, Serbia · Feb 2023 – Present

- Develop and maintain high-load payment services in Kotlin and Java; reactive architecture with Project Reactor.
- Ensure PCI-DSS compliance and transaction security; integrate external payment systems.
- Manage inter-service messaging over RabbitMQ; drove a GraalVM native-image migration that reduced memory footprint and CPU time by 80%, saving ~EUR 20k/month.
- Build CI/CD pipelines (GitLab) with automated testing (JUnit, TestContainers).

### Software Engineer — Perfect Art
Belgrade, Serbia · May 2022 – Feb 2023

- Architected a financial-activity screening system for small businesses.
- Implemented core logic in Scala + Akka for a highly concurrent, resilient solution.

### Software Engineer — MTS
Moscow, Russia · May 2020 – May 2022

- Designed a real-time, high-load streaming platform processing **15M+ messages/sec** from Kafka.
- Built the core processing engine in Java + Akka Streams; wrote consumer services in Scala (ScalaTest).
- Used Aerospike for caching and deduplication; managed inter-service communication through Kafka.

### Software Engineer — Raiffeisen Bank
Moscow, Russia · May 2018 – Aug 2019

- Built and enhanced a high-load notification service in Java + Spring Integration; rewrote the mass-mailing flow.
- Redesigned caching mechanisms to improve performance; built a notification-history service from scratch.
- Contributed to frontend work with React and WebSockets for real-time communication.

### Earlier (2016 – 2019)
Java & Android roles at Alfa-Bank, EPAM Systems, Trendsoft, and Dixy — core banking (OpenID Connect authentication), high-load data-validation systems and REST APIs, system integrations (1C, AmoCRM), and mobile development (Retrofit, RxJava).

---

## Skills

- **Languages:** Java, Kotlin, Scala, Rust, Python, TypeScript, SQL
- **Frameworks & Reactive:** Spring Boot, Spring Integration, Project Reactor, Akka Streams, ZIO, Tokio, RSocket, NestJS
- **Messaging & Streaming:** Apache Kafka, RabbitMQ
- **Data & Caching:** PostgreSQL, Aerospike, Redis
- **AI & Event-Driven:** event-driven architecture, gRPC, LLM-backed systems, auditable/reproducible decision pipelines
- **DevOps & Tooling:** Docker, GitLab CI/CD, Gradle, TestContainers, JUnit, Git, GraalVM

---

## Projects

- **AlladinAi** — Event-driven algorithmic-trading platform with an architecturally unbypassable risk engine and reproducible, auditable decisions. *Rust, Tokio, Python, Kafka, gRPC.*
- **HealthTracer** — AI health coach built as a system, not a chatbot: a Postgres-backed structured domain model is authoritative, while the AI emits *typed proposals* (never direct DB writes) that the backend validates and the user approves, each becoming an immutable, auditable revision. The core is a multi-domain fan-out & synthesis LLM pipeline (a router selects up to 3 domains, runs them in parallel, then a decision-maker synthesizes their output into proposals) with a deterministic planner clamping output to a hard capability allowlist and safety floors enforced in code. *TypeScript, NestJS, Next.js, Expo, Drizzle/PostgreSQL, Turborepo.*
- **BeoSand** — Telegram-first platform for booking volleyball courts and managing training in Belgrade: a React admin console (scheduling, court-load heatmap, booking requests, broadcasts) plus a Telegram mini-app for players (browse slots, book, waitlist). Server-authoritative by design — all pricing, availability, and capacity are computed server-side and the UI only displays values and collects actions. Telegram Login auth, RSD pricing, RU/SR/EN i18n. *TypeScript, React + Vite, Telegram Mini Apps.*
- **payment-system-demo** — Distributed payment system communicating over sync + async channels. *Java, Spring Security, Spring Integration, JWT, MQ.*

---

## Education

**HSE University** — B.Sc., Software Engineering · 2014 – 2018

---

## Certifications

- JVA-074 Java Advanced: Functional, Asynchronous and Reactive Programming
- Kotlin Developer

---

## Languages

- English — Advanced (C1)
- Russian — Native
