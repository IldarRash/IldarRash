---
layout: default
---

<style>
.btn {
  display: inline-block;
  padding: 8px 18px;
  margin: 4px 6px 4px 0;
  font-size: 1rem;
  font-weight: 500;
  color: #fff;
  background: #007bff;
  border: none;
  border-radius: 4px;
  text-decoration: none;
  transition: background 0.2s;
  cursor: pointer;
}
.btn-primary {
  background: #007bff;
}
.btn:hover, .btn:focus {
  background: #0056b3;
  color: #fff;
  text-decoration: none;
}
</style>

# Ildar Shayakhmetov
*Senior Backend & AI-Systems Engineer — High-Load Fintech*

[Download CV](./ildar_shaiakhmetov.pdf){: .btn .btn-primary}
[Email Me](mailto:il.sach@yandex.ru){: .btn}
[LinkedIn](https://www.linkedin.com/in/ildar-shayakhmetov-8471ab164){: .btn}
[GitHub](https://github.com/IldarRash){: .btn}

---

## Professional Summary

A results-driven **Senior Backend & AI-Systems Engineer** with over 6 years of experience designing high-load, distributed backend systems. Proficient in **Java**, **Kotlin**, and **Scala**, with a strong focus on reactive programming using **Project Reactor** and **Akka Streams**, and deep experience in **fintech** — payments, money movement, and PCI-DSS-compliant services. Alongside JVM work, I architect **event-driven AI platforms** in **Rust** and **Python** (algorithmic trading, AI health coaching). Proven ability to lead projects, optimize performance, and keep systems stable under load.

---

## Key Achievements

- 🚀 Engineered a real-time streaming platform processing **5M+ messages/sec** from Kafka (Java + Akka Streams).
- 💳 Deliver **PCI-DSS-compliant** payment services in production at Paysend (Kotlin, Project Reactor).
- 💰 Reduced cloud spend by **~€20k/month** via a GraalVM native-image migration.
- 🦀 Architected an event-driven algorithmic-trading platform with an **unbypassable risk engine** (Rust + Python + Kafka).

---

## Work Experience

### **Software Developer**
**Paysend** | *Belgrade, Serbia*
*February 2023 - Present*

- Develop and maintain high-load payment services using Kotlin and Java, ensuring robustness and scalability.
- Architect and implement reactive solutions with Project Reactor to handle asynchronous data streams efficiently.
- Integrate with third-party payment systems, focusing on transaction security and PCI DSS compliance.
- Manage microservices communication using RabbitMQ and enhance system performance and scalability.
- Implement comprehensive automated testing with JUnit and TestContainers within a GitLab CI/CD pipeline.
- Take part in the technical hiring process — conducting interviews — and in prioritizing the team's backlog.

### **Software Engineer**
**Perfect Art** | *Belgrade, Serbia*
*May 2022 - February 2023*

- Architected and developed a system for screening the financial activity of small businesses.
- Implemented the core logic using Scala and the Akka framework for a highly concurrent and resilient solution.
- Coached teammates on the Scala/Akka codebase and the screening domain to raise delivery quality.

### **Software Engineer**
**MTS** | *Moscow, Russia*
*May 2020 - May 2022*

- Designed and developed a real-time, high-load data streaming platform processing over 5 million messages per second from Kafka.
- Utilized Java and Akka Streams for the core processing engine, ensuring high throughput and low latency.
- Wrote consumer services in Scala, leveraging ScalaTest for robust testing.
- Managed inter-service communication through Kafka and utilized Aerospike for caching and deduplication.
- Mentored interns and new hires and delivered internal Scala lectures to accelerate team ramp-up.

### **Software Engineer**
**Raiffeisen Bank Russia** | *Moscow, Russia*
*May 2018 - August 2019*

- Developed and enhanced a high-load notification service using Java and Spring Integration.
- Rewrote mass mailing functionality and redesigned caching mechanisms to improve performance.
- Contributed to frontend development with React, utilizing WebSockets for real-time communication.
- Built a notification history service from the ground up.

---

## Core Skills

- **Languages:** Kotlin, Java, Scala, Rust, Python, TypeScript
- **Frameworks & Reactive:** Spring Boot, Spring Cloud Gateway, Spring WebFlux, Project Reactor, Akka Streams, ZIO, ZIO HTTP, Tokio, RSocket, NestJS
- **AI & Event-Driven:** event-driven architectures, gRPC, FlatBuffers, LLM-backed systems, reproducible/auditable decision pipelines
- **Messaging & Streaming:** Apache Kafka, RabbitMQ, RSocket
- **Databases & Caching:** PostgreSQL, MongoDB, Aerospike, Redis, Quill
- **DevOps & Tools:** Docker, Kubernetes, GitLab CI, GraalVM, TestContainers, Gradle, Git

---

## Education

**HSE University**
*Bachelor's degree, Software Engineering*
*2014 - 2018*

---

## Certifications

- **JVA-074 Java Advanced:** Functional, Asynchronous and Reactive Programming
- **Kotlin Developer**

---

## Highlighted Projects

- **[Alladin](https://github.com/IldarRash/AlladinAi)**: Event-driven algorithmic-trading platform with an architecturally unbypassable risk engine — Rust, Tokio, Kafka, gRPC.
- **[HealthTracer](https://github.com/IldarRash/HealthTracer)**: AI health coach built structured-state-first (state is authoritative, chat is just the interface) — TypeScript, NestJS, Next.js, Drizzle.
- **[bot-constructor](https://github.com/IldarRash/bot-constructor)**: Microservices automation platform for visually building bots with an n8n-style workflow engine — React Flow node-graph UI over a reactive Kotlin backend (gateway/auth/client-api/bot-api); an item-based engine runs 23 node types (triggers, branches, code, live connectors to Claude/Telegram/Slack/Discord), a sandboxed GraalVM JavaScript evaluator, an AES-256-GCM-encrypted credential store, per-node execution history, and cron scheduling; RSocket transport, WebFlux, MongoDB, Docker + Kubernetes — Kotlin, Spring Boot 4, Spring Cloud Gateway, RSocket, WebFlux, MongoDB, GraalVM, React 19 / React Flow.
- **[zio-avito-desk](https://github.com/IldarRash/zio-avito-desk)**: Full-stack classifieds board built functional-first — layered Scala 3 + ZIO backend, ZIO HTTP, compile-time type-safe SQL via Quill, ZLayer DI; session-cookie auth with bcrypt, ownership-gated CRUD, image uploads, PostgreSQL with Flyway migrations, 33 Testcontainers tests, React 19 frontend, GitHub Actions CI — Scala 3.3, ZIO 2, ZIO HTTP 3, Quill, PostgreSQL, Flyway, React.
- **[BeoSand](https://github.com/IldarRash/BeosendApp)**: Telegram-first platform for booking volleyball courts in Belgrade — server-authoritative pricing/availability, React admin console + Telegram mini-app, RU/SR/EN i18n — TypeScript, React + Vite, Telegram Mini Apps.