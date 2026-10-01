# Edjutawee Dawit

**AI Research Engineer | Reliable Inference, Scaling Laws & ML Infrastructure**

📍 Atlanta, GA / Remote | 📧 edjutaweedawit@gmail.com | 🔗 [LinkedIn](https://linkedin.com/in/edjutawee) | 🐙 [GitHub](https://github.com/edawite) | 🇺🇸 U.S. Citizen

Welcome to my portfolio. I am a Research Engineer focused on building robust empirical evaluations, high-performance ML infrastructure, and understanding neural scaling laws.

---

## 📄 Master Resume

### EDUCATION
**Purdue University** | *B.S. in Artificial Intelligence* | Expected May 2027
* **GPA:** 3.5 | **Achievements:** USACO Platinum, ICPC Regional Preparation, Putnam Participant
* **Coursework:** Data Structures & Algorithms, Object-Oriented Programming, Data Engineering in Python

---

### EXPERIENCE

**Microsoft** | *Incoming Software Engineer Intern* | Redmond, WA (May 2026 – Aug 2026)
* Selected for Microsoft’s 2026 Software Engineering Internship, joining Azure’s backend and applied-AI teams.
* Will contribute to large-scale distributed systems and intelligent service integration across Azure infrastructure.

**Eli Lilly** | *LLM Researcher* | Indianapolis, IN (Nov 2025 – May 2026)
* Engineered a modular Python framework leveraging LLMs to enrich cybersecurity indicators with automated tagging, contextual narratives, and inter-indicator relationship mapping.
* Designed a production-ready architecture with Dockerized deployment, JSON-based data contracts, and extensible APIs for integration into enterprise threat analysis pipelines.

**NASA Earth Science Technology Office (ESTO)** | *Software Engineer Intern* | Remote (May 2025 – Aug 2025)
* Engineered a hybrid flood detection system achieving **0.92 IoU with 10× CPU speedup** vs UNet baseline through a **PyTorch→ONNX→TensorRT** optimization pipeline for edge deployment.
* Developed a real-time SAR image processing pipeline for Sentinel-1 satellite tiles, achieving **250ms inference latency** and enabling a 5% faster flood detection response.
* Architected a modular, fault-tolerant system with a reproducible evaluation harness, improving challenge submission scores by 8%.

**Purdue University** | *Backend / Computational Researcher* | West Lafayette, IN (Jan 2025 – May 2025)
* Built a distributed document processing pipeline using **Python multiprocessing + Redis**, achieving **100+ papers/hour throughput** across 2,000+ academic papers with 95% automation accuracy.
* Engineered a fault-tolerant system with checkpointing and idempotent job processing, deployed on **AWS EC2 spot instances** with auto-scaling capabilities.
* Implemented comprehensive monitoring with **Prometheus metrics and Grafana dashboards** tracking p95 latency, throughput, and cost optimization.

**CorpusKey** | *Full-Stack Engineer Intern* | Indianapolis, IN (Jun 2024 – Aug 2024)
* Designed an AI-powered lesson planning platform serving 500+ educators with **React + Flask microservices**, achieving 99.5% uptime and a 70% reduction in planning time.
* Implemented ChatGPT API integration with rate limiting and caching; optimized PostgreSQL queries with indexing strategies for **sub-100ms response times**.
* Created a CI/CD pipeline with **GitHub Actions and Docker** containerization; reduced production deploy time from 15 minutes to 3 minutes with zero-downtime releases.

---

### PUBLICATIONS & RESEARCH

**FinRL Contest 2025 Task 1: Reinforcement Learning for SPY Trading** 
*Accepted to IEEE IDS 2025 Special Track on FinRLFM (Withdrawn due to funding); Preprint available*
* Evaluated 5 RL algorithms (DQN, Double DQN, PPO, SAC, A2C) in continuous environments for trading the SPY ETF.
* Integrated DeepSeek LLM sentiment scores to improve the A2C portfolio's Sharpe Ratio by 12%.

**A Two-Phase Scaling Law for Neural Chess Search** 
*Preprint / IEEE CoG 2026 Submission*
* Designed and parallelized a fixed-anchor tournament of **7,000+ games** across an **HPC cluster** to evaluate Stockfish 16 (NNUE) scaling efficiency.
* Identified a Two-Phase scaling law, demonstrating that highly accurate neural priors reduce the marginal utility of deep search by ~66% (+34 Elo per ply) relative to classical baselines.

**When Annealed Causal Erasure Fails to Induce Algorithmic Transfer**
*Submitted to NeurIPS 2026 PriGM Workshop*
* Implemented a custom training intervention (Annealed Causal Erasure) to suppress operand-position residual states in Transformers.
* Analyzed grokking and representation transfer across 24 modular-inversion runs, identifying a 100% train / 0% test separation.

---

### TECHNICAL PROJECTS

**Independent AI Researcher (Chess RL Agent)** | *Winter 2024*
* Developed a reinforcement learning chess agent trained via self-play and policy gradients.
* Automated gameplay via Selenium, training the agent to 1800 Elo (top 15% of players) in 500+ self-play episodes.

**LLMOps Monitoring Platform**
* Designed a multi-tenant dashboard tracking token latency, cost, and accuracy across distributed LLM endpoints.
* Achieved **<50ms p95 refresh rates** with persistent log storage and automated alerting on performance degradation using AWS EC2, Docker Compose, Nginx, and end-to-end TLS.

**Serverless Image-Processing Pipeline**
* Built an end-to-end pipeline triggered by AWS S3 events that converts uploads into WebP thumbnails, processing 1,000+ images/min.
* Optimized cold-start latency to 250ms via provisioned concurrency and asynchronous SQS buffering, deployed via Terraform and AWS SAM.

---

### TECHNICAL SKILLS
* **Programming Languages:** Python, C++, Java, JavaScript, TypeScript, SQL, Bash, C#
* **Systems & Performance:** Docker, Kubernetes, Redis, Ray, PyTorch Lightning, ONNX, TensorRT, Linux, CUDA
* **Backend & APIs:** FastAPI, Flask, Node.js, REST APIs, GraphQL, gRPC
* **Cloud & Infrastructure:** AWS (EC2, Lambda, S3, EKS), Terraform, CI/CD, GitHub Actions
* **Data & Observability:** Prometheus, Grafana, CloudWatch, Kafka, Spark, OpenTelemetry
