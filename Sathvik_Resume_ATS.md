Vutukuri Sathvik
Full-Stack Engineer | Backend & Distributed Systems

Location: Bengaluru, India
Email: 7vik.sathvik@gmail.com
Phone: 8197748291
Website: pa1sathvik.github.io
LinkedIn: linkedin.com/in/sathvik-v

SUMMARY

11+ years as a full-stack engineer building complete products end to end - from large-scale backend and distributed systems in Java (high-throughput messaging, distributed scheduling, decisioning infrastructure) to the React web portals and dashboards on top. Deepest on the systems side, owning architecture through production delivery at scale (platforms serving 1B+ requests/day), and comfortable across the full stack.

SKILLS

Languages: Java (8 to 25), JavaScript, SQL
Distributed Systems: System Design, Distributed Scheduling, Event-Driven Architecture, Consistency and Idempotency, High Throughput, Fault Tolerance
Concurrency: Virtual Threads, Structured Concurrency, CompletableFuture, Multithreading
Backend: Spring Boot, GraphQL, REST, Microservices, gRPC
Messaging and Streaming: Kafka, Pulsar
Data and Storage: Bigtable, Oracle, MongoDB
Cloud and Infrastructure: GCP, GKE, Kubernetes, Docker, Amazon S3
Frontend: React JS, Redux, JavaScript, Tailwind, HTML/CSS
Observability: Datadog, Grafana, Prometheus, Micrometer, OpenTelemetry
Foundations: Data Structures and Algorithms, OOP, Design Patterns

EXPERIENCE

Member of Technical Staff I (Backend Architect)
PayPal | Bengaluru, India | Apr 2022 to Present

KAIROS - Communication Decision Platform
- Designed core components of KAIROS, PayPal's Communication Decision Platform, the centralized layer that governs what every consumer is communicated, when, and on which channel. Designed, delivered, and running in production.
- Designed the Intent Management System (IMS), the ingestion and management layer for decision intents flowing into the platform from producing systems.
- Architected the Deferred-Intent Scheduler, a durable, leaderless distributed timer on Google Bigtable and Pulsar sized for approximately 25 to 30 million deferred intents per day with bursts up to 2 million due at once. Used per-row atomic compare-and-set (checkAndMutate) claims for single-fire dispatch and Kafka consumer-group hash-partitioning for leaderless work distribution across autoscaling instances.
- Owned the Scheduler's end-to-end low-level design: hash-prefixed row-key schema for even node distribution, scan-claim-dispatch pipeline, cell-timestamp-based garbage collection, failure recovery, and at-least-once dispatch with idempotent re-evaluation.
- Evaluated alternative Bigtable data models (row-per-intent versus wide-row bucketing) with DBA architects, selecting the design that preserved write parallelism at burst scale.
- Designed part of the Ledger component and defined the ingestion and dispatch contracts integrating the Scheduler with the Decision Engine's trigger pipeline.

PayPal Communications - Comms Platform
- Architected and own the end-to-end backend platform powering all PayPal communications: sending, scheduling, and delivering across Push, Notification Center, Critical Alert, and Silent Push for PayPal, Venmo, and Xoom tenants.
- Driving the communications platform revamp, redesigning service architecture for scalability, multi-region support, and integration with the centralized decisioning layer.
- Designed and built Beacon, the production web portal for PayPal Communications used company-wide to schedule and manage communications. Owned it end to end (React frontend).
- Made the comms platform a producer of intent objects so every send/suppress/defer decision is centrally evaluated against eligibility, ML scoring, cap enforcement, and quiet hours.

Verse - Long-Form Content Platform
- Designed the backend and end-to-end flow for Verse, a modular, partly server-driven platform that lets product teams ship content experiences (FAQs, terms and conditions, education pages) without building custom UI each time.
- Architected it for multi-tenant use across PayPal, Venmo, and Xoom via a shared core with tenant-specific modules, driving content and predefined design-system templates from the server with context-aware rendering and offline-capable caching.
- Built the backend for the admin tool and defined the client SDK contract - single-call integration, deep-linkable pages, and multiple presentation modes.

Server-Driven UI (SDUI) Platform
- Led backend for PayPal's in-house Server-Driven UI platform, built from scratch and shipped to production, serving 1 billion+ requests per day and powering core PayPal app and web experiences.
- Architected core SDUI services: version management, page inheritance, schema versioning, and database design, enabling consistent UI delivery across iOS, Android, and Web.

Recognition: PayPal SPOT Awards, Q3 2022 and Q4 2023.

Senior Software Engineer
Informatica | Bengaluru, India | Mar 2020 to Apr 2022
- Architected and built SecureStats end to end, a security-flaw management platform with full backend, frontend, database design, and APIs.
- Co-designed Flaw Management Service and Notification Service in a microservices architecture.
- Mentored 5 engineers on service design and architecture decisions. INFASTAR Award Q1 2021.

Senior Software Engineer
Envestnet Yodlee | Bengaluru, India | Nov 2015 to Mar 2020
- Architected Juggernaut, a microservice platform for automated issue resolution on Yodlee PFM. Owned end-to-end backend and frontend design.
- Designed observability stack with Spring Boot Actuator, Micrometer, Prometheus, and Grafana; microservice infrastructure with Eureka, Zuul, and Hystrix.
- Yodlee Dream Team Award, Juggernaut R&D (Q2 2018, Q2 2019).

SELECTED TECHNICAL HIGHLIGHTS

- Distributed scheduling at scale: designed a durable, leaderless timer on Bigtable and Pulsar for approximately 25 to 30 million deferred intents per day with 2 million-at-once bursts, using per-row atomic compare-and-set for single-fire dispatch without a coordinator.
- High-throughput serving: led the backend for a Server-Driven UI platform serving 1 billion+ requests per day across iOS, Android, and Web.
- Schema and storage design: evaluated competing Bigtable data models with DBA architects and chose the design that preserved write parallelism under burst load.
- Messaging and event-driven systems: built platforms on Kafka and Pulsar spanning ingestion, scheduling, and dispatch, with idempotent, at-least-once delivery semantics.
- Full-stack delivery: built React web portals and admin dashboards on top of the backend systems (e.g. Beacon), owning features from data model to UI.
- End-to-end ownership: consistently took systems from problem statement and architecture through low-level design, implementation, and production rollout.

EDUCATION

B.Tech, Computer Science and Engineering
JNTU Kakinada | 2011 to 2015 | GPA 7.9/10

AWARDS

- PayPal SPOT Awards (SDUI): Q3 2022, Q4 2023
- Informatica INFASTAR (SecureStats): Q1 2021
- Yodlee Dream Team (Juggernaut R&D): Q2 2018, Q2 2019
- Yodlee Spot Awards: Q2/Q3 2016, Q1 2018, Q3 2019
