# Hi, I'm Navtej Nair 👋

Software engineering student building correctness-critical, concurrent backend systems — from sandboxed code execution platforms to metadata-driven data pipelines. Currently deep in distributed systems and infrastructure.

🎓 M.Tech Integrated Software Engineering @ VIT Chennai (2022–2027)
🔭 Currently building a multiplayer real-time chess platform (Java, Spring Boot, WebSockets) and an autonomous AI coding agent from scratch
🌱 Learning: distributed consensus, sharding, and stateful-system resilience at scale
📫 Reach me: nairnavtej@gmail.com · [LinkedIn](https://linkedin.com/in/navtejnair)

---

## 🛠️ What I work with

**Languages:** Java · C/C++ · Python · SQL · T-SQL · Dart

**Backend & Systems:** Spring Boot · REST APIs · Multithreading · ExecutorService · ConcurrentHashMap · Rate Limiting · Distributed Locks · Circuit Breakers · Load Balancing · Message Queues (Kafka/RabbitMQ) · Redis

**Infra & Tools:** Docker · Redis Pub/Sub · WebSockets · Git · Maven/Gradle

**Data Engineering:** Microsoft Fabric · PySpark · Delta Lake · ETL/ELT Pipeline Design

**AI Agent Systems:** LLM Tool-Calling Loops · LangChain · GitHub App Auth (JWT) · Sandboxed Execution

---

## 🚀 Featured Projects

### 🖥️ [Online GDB — Sandboxed Code Execution Platform](https://github.com/navtej21/online-gdb)
A Judge0-style multi-language code execution sandbox. Untrusted submissions run inside ephemeral, resource-capped Docker containers (`--memory`, `--cpus`, `--pids-limit`, `--network=none`), with async result delivery via Redis Pub/Sub + WebSocket so the API never blocks on container runtime.
`Java` `Spring Boot` `React` `Docker` `Redis` `WebSockets`

### 🤖 Cloud Coding Agent — Autonomous AI Development Assistant
A Devin/Cursor-style autonomous coding agent built from scratch — full agentic tool-calling loop (model call → stop-reason routing → tool execution → result feedback), sandboxed execution, GitHub App authentication.
`Python` `LLM Tool-Calling` `Docker` `Redis Streams` `Spring Boot`

### 🗃️ IngestXcel — Metadata-Driven Data Ingestion Framework
A metadata-driven migration framework on Microsoft Fabric automating ingestion from 4+ heterogeneous source systems into a governed Bronze/Silver architecture, with incremental logic (SCD Type 1/2) validated against production-scale datasets.
`Microsoft Fabric` `PySpark` `Delta Lake` `T-SQL`

### 💻 CodeRun — Real-Time Collaborative Code Editor *(in progress)*
A CodeShare.io-style collaborative editor that adds what the original lacks entirely: live code execution. Room-based WebSocket broadcast for multi-user editing, sandboxed Docker execution reused from Online GDB, with debounced auto-run and live test-case pass/fail as differentiators over existing tools.
`Java` `Spring Boot` `React` `Docker` `WebSockets`

### ⚡ Concurrent Request Filtering & DDoS Simulation
Multithreaded request-processing system with IP-based rate limiting, sustaining 5,000+ req/sec across 50 simulated clients while blocking 90%+ of malicious traffic within 1 second, zero false positives.
`Java` `ExecutorService` `BlockingQueue` `ConcurrentHashMap`

---

## 📊 GitHub Stats

![Navtej's GitHub stats](https://github-readme-stats.vercel.app/api?username=navtej21&show_icons=true&theme=default)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=navtej21&layout=compact)

---

## 📝 Recent writing / links

- LeetCode · GFG *(add profile links)*
- [Published: ML-Based Sentiment Analysis of Twitter Using Logistic Regression](#) *(IGI Global)*

---

⭐️ Always open to conversations about distributed systems, backend infra, and correctness-critical engineering.
