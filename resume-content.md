<!-- Text from resume.html via build-resume.py. Memory figures clarified by the author on 7 Sep 2026. -->

ILDAR SHAYAKHMETOV
Senior / Staff Software Engineer | AI Products | Zero-to-One Engineering
il.sach@yandex.ru  |  +381 62 975 4956  |  Belgrade, Serbia
linkedin.com/in/ildar-shayakhmetov-8471ab164  |  github.com/IldarRash  |  ildarrash.github.io/IldarRash
Summary
Hands-on senior/staff engineer with 10 years of experience building backend platforms and product surfaces across AI,
fintech, analytics, telecom, and banking. Strongest when an idea is still rough: clarify the user problem, challenge
unnecessary scope, choose an architecture that can ship, and stay with the feature through production. Deep in
distributed JVM systems, with practical full-stack delivery in TypeScript, React, Next.js, Expo, and Telegram Mini Apps.
Has led backend teams, reviewed product and technical decisions, mentored engineers, and built several independent
products from zero.
Core Skills
- Product ownership: turn ambiguous ideas into user flows, technical decisions, working software, and operational
feedback
- AI product systems: LLM orchestration, typed proposals, deterministic validation, capability boundaries, audit
history, human approval
- Full-stack delivery: TypeScript, NestJS, React, Next.js, Expo, React Flow, REST APIs, authentication, scheduling,
internationalization
- Backend depth: Java, Kotlin, Scala, Rust, Spring Boot, Project Reactor, Akka Streams, Kafka, RabbitMQ,
PostgreSQL, Redis
- Engineering leadership: architecture direction, design and code reviews, prioritization, mentoring, hiring, cross-team
alignment
Projects
HealthTracer - AI health companion platform
Turned a broad AI-coach idea into a structured product across mobile, web, and backend. Designed a multi-domain
LLM pipeline where the model proposes typed changes, while the backend validates them and the user approves each
immutable revision. Added a deterministic planner, explicit capability boundaries, and code-enforced safety floors so the
product remains useful without giving the model unchecked authority. TypeScript, NestJS, Next.js, Expo, PostgreSQL.
bot-constructor - visual automation product
Built the product end to end: React Flow interaction model, four reactive Kotlin services, and an execution engine for 23
node types including triggers, branches, HTTP, sandboxed code, schedules, and AI/service connectors. Owned the less
visible product work too - encrypted credentials, per-node history, failure visibility, and deployable Docker/Kubernetes
packaging. Kotlin, Spring WebFlux, RSocket, MongoDB, React.
BeoSand - Telegram-first booking product
Built a player-facing Telegram Mini App and a React admin console for real booking operations in Belgrade. Kept
pricing, availability, and capacity server-authoritative while making the user flow quick and understandable; added
scheduling, booking requests, broadcasts, and RU/SR/EN localization. TypeScript, React, Vite, Telegram Mini Apps.
Professional Experience
Software Developer - Paysend
Feb 2023 - Jun 2026
Belgrade, Serbia
- Owned production payment services in Java and Kotlin, from implementation and external integrations through
testing, delivery, and operational follow-up.
- Delivered PCI-DSS-compliant functionality and transaction-security controls for critical money-movement flows.
- Led a GraalVM native-image migration: average memory use fell from about 20 MB to under 2 MB, and allocated
memory from 200 MB to 20 MB. The migration saved approximately EUR 20,000 per month in cloud costs.
- Improved asynchronous RabbitMQ interactions and GitLab CI/CD with JUnit and Testcontainers; contributed to hiring
and backlog decisions.


Professional Experience - Continued
Team Lead - Prizma.tools
Nov 2021 - Jan 2023
- Led a small backend team building an analytics product, translating incomplete stakeholder ideas into concrete
priorities, architecture, and shipped services.
- Stayed hands-on while setting direction for fault-tolerant services, data pipelines, storage, caching, and asynchronous
processing.
- Introduced practical review, testing, monitoring, and refactoring habits; mentored engineers and spread ownership
instead of centralizing every decision.
Software Engineer - MTS
Aug 2019 - Oct 2021
Moscow, Russia
- Designed a real-time platform processing more than 5 million Kafka messages per second in aggregate across the
platform, where backpressure, latency, deduplication, and failure behavior were product constraints rather than
afterthoughts.
- Built the core engine in Java and Akka Streams and consumer services in Scala; used Aerospike caching to protect
high-volume data flows from duplicate work and avoidable latency.
- Mentored interns and new hires and ran internal Scala sessions to shorten the path from unfamiliar code to useful
contribution.
Software Engineer - Raiffeisen Bank
May 2018 - Aug 2019
Moscow, Russia
- Built and evolved a high-load notification product in Java and Spring Integration, including a rewritten
mass-notification flow and a new history service.
- Redesigned caching and added React/WebSocket functionality so users received faster, clearer feedback from
backend events.
Earlier Engineering Roles - EPAM Systems, Trendsoft, Dixy
2016 - 2019
Delivered data-validation services and REST APIs, integrated business systems including 1C and AmoCRM, and
developed Android applications with Retrofit and RxJava.
Selected Engineering Outcomes
- Shipped systems ranging from consumer mobile and web products to payment services and a streaming platform
processing 5M+ messages/second in aggregate.
- Reduced production infrastructure cost by approximately EUR 20,000 per month through a measured runtime
migration.
- Built product logic where correctness matters: payment controls, server-authoritative pricing and capacity, typed AI
proposals, and auditable decisions.
- Worked across the whole delivery loop: shaping requirements, architecture, implementation, tests, CI/CD, production
diagnosis, and follow-up improvements.
Technical Skills
- Languages: Java, Kotlin, Scala, Rust, TypeScript, Python, SQL
- Product & Web: React, Next.js, Expo, React Flow, Telegram Mini Apps, REST, WebSockets, i18n
- Backend & Data: Spring Boot, Spring WebFlux, Project Reactor, Akka Streams, NestJS, Kafka, RabbitMQ,
PostgreSQL, MongoDB, Aerospike, Redis
- AI Systems: LLM-backed workflows, multi-agent fan-out and synthesis, typed outputs, deterministic planners,
human-in-the-loop approval
- Delivery: Docker, Kubernetes, GitLab CI/CD, GitHub Actions, GraalVM, JUnit, Testcontainers, Git
Education & Languages
HSE University - B.Sc. in Software Engineering, 2014 - 2018
English - Advanced (C1)  |  Russian - Native
