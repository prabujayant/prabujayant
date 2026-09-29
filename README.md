<div align="center">

# Hi, I'm Prabu Jayant 👋

**Software Engineer at Baker Hughes · Published ML Researcher · Bengaluru, India**

[Portfolio](https://prabujayant.vercel.app) · [LinkedIn](https://www.linkedin.com/in/prabu-jayant-6b316b251/) · [Email](mailto:prabu.jayant2022@gmail.com)

</div>

---

## About

I'm a software engineer and published ML researcher at **Baker Hughes**, where I build AI-assisted
products — document-classification models that keep people in the loop, and platforms that quietly
absorb the repetitive parts of real work.

Earlier at **Juniper Networks** I worked on high-throughput network analytics, processing 1M+ daily
packets for real-time security monitoring.

Underneath all of it, I care about software that is reliable, observable, and pleasant to work with.
Most of what I build ends up published — **5 papers**, 34 citations, h-index 2.

### Currently

- 🔭 Building AI-assisted document classification and internal tooling at Baker Hughes
- 🌱 Learning deeper distributed-systems patterns and better anomaly detection
- 💻 Shipping side projects in RAG, real-time collaboration, and web tooling
- 🎯 Open to collaboration on AI, security, and distributed systems

---

## Experience

### Baker Hughes — Development Engineer
`Jan 2026 – Present`

- Designed and trained a hybrid **BERT-CNN** NLP model for automated document classification at
  **85% accuracy**, adding human-in-the-loop validation that cut manual audit effort by **50+ hours/week**.
- Engineered a full-stack classification platform (Python, Flask, React, PostgreSQL) with automated
  message queues, scaling partner intake throughput **3x** across regional enterprise teams.
- Architected production microservices on **Azure App Service** with Microsoft Entra ID RBAC and
  GitHub Actions CI/CD, cutting deployment cycle times by **40%** under a zero-trust model.
- Promoted from Digital Technology Intern to Development Engineer after shipping the classification
  platform to production.

### Juniper Networks — Software Engineering Intern, Data & Analytics
`Jul 2024 – Feb 2025`

- Engineered a high-throughput Python pipeline handling **1M+ daily network packets**, enabling
  real-time monitoring and automated labeled datasets for security analytics research.
- Built and statistically tuned a microservice classification platform reaching **98% accuracy** on
  network service identification, lowering system latency by **25%**.
- Established automated unit testing and validation frameworks in an Agile R&D workflow, reducing
  dataset error rates by **30%** while holding production SLA compliance.

### Education

**RV College of Engineering, Bengaluru** — B.E. Computer Science and Engineering (Cybersecurity)
`2022 – 2026` · CGPA 8.87

---

## Projects

### [CoLab](https://github.com/prabujayant/CoLab) — Real-time Collaborative Editor
`TypeScript · React · Node.js · Redis · PostgreSQL · CRDTs · WebSockets · Docker`

A high-performance collaborative text editor with conflict-free synchronization, live presence
cursors, and deep versioning built around CRDT principles.

- Designed the Y.js + WebSocket architecture and compressed snapshot persistence in PostgreSQL.
- Implemented JWT-based auth with session rotation.
- Shipped with a real-time observability dashboard for system metrics and active user sessions.

### [AskMyDocs](https://github.com/prabujayant/RAG) — Grounded RAG Q&A
`Python · FastAPI · Qdrant · Celery · BAAI/bge-m3 · RAGAs · Next.js`
**[Live demo →](https://prabu17-askmydocs.hf.space/)**

Retrieval-augmented Q&A over mixed-format technical documentation. Every claim in an answer is
labelled, so unsupported claims are *visible* rather than hidden.

- Built hybrid retrieval: **BGE-M3** dense vectors in Qdrant fused with Postgres `tsvector` keyword
  search via reciprocal-rank fusion.
- Reranked with a multilingual cross-encoder; added a claim-level LLM judge that labels each answer
  `grounded`, `partially grounded`, `ungrounded`, or `refused`.
- Shipped a RAGAs evaluation harness against a 60-question golden set with regression thresholds,
  plus deterministic screening for prompt injection and PII.

### [DefenSys](https://github.com/prabujayant/DefenSys) — Intelligent Cyber Defense Platform
`C/C++ · Python · PyTorch · Docker · Kubernetes · Redis · Linux`

Full-stack cyber defense platform with real-time threat visualization and containerized IoT
simulation, so teams can validate automated defenses without touching production systems.
Published at **ICOSEC 2025**.

### [PrabuWeb](https://github.com/prabujayant/PrabuWeb) — Portfolio Site
`TypeScript · Next.js 16 · React 19 · Tailwind CSS · MDX · Vercel`

This site. A single-scrolling portfolio with a typed content layer, MDX-backed long-form content, and
a fully static build — copy changes never require component edits.

---

## Publications

1. **CASB Security Analytics for Encrypted SaaS Traffic: A Hybrid Transformer-Based Classification
   Framework in Enterprise Cloud Ecosystems** — *IEEE Access*, 2025
   · [Link](https://scholar.google.com/citations?user=s4ldIOYAAAAJ&hl=en&oi=sra)
2. **DefenSys: An Integrated Platform for Malware Detection and Containerized Attack Simulation Using
   Deep Learning** — *ICOSEC*, 2025 · [Link](https://ieeexplore.ieee.org/document/11459625/)
3. **Adaptive ML Framework for SaaS Traffic Classification in Cloud Ecosystem** — *ICWIHMI*, 2025
   · [Link](https://drive.google.com/file/d/1B3tt_W8u3wbktvR13hm7hObToNdV87Ww/view)
4. **Smart Health Monitoring and Anomaly Detection Using IoT and AI** — *ICICPS*, 2024
   · Cited by 26 · [Link](https://ieeexplore.ieee.org/document/10724486)
5. **Intrusion Detection in Network Traffic Using LSTM and Deep Learning** — *IEEE ICCCNT*, 2024
   · Cited by 7 · [Link](https://ieeexplore.ieee.org/document/10696283)

---

## Skills

| Area | Technologies |
| --- | --- |
| **Languages** | C/C++, Python, Java, TypeScript, JavaScript, SQL |
| **Frontend** | React, Next.js, HTML5, Tailwind CSS |
| **Backend** | REST APIs, Microservices, Node.js, FastAPI, Flask, Redis queues, WebSockets |
| **Databases** | PostgreSQL, MongoDB, Redis, pgvector, Qdrant, Firebase |
| **AI / ML** | PyTorch, TensorFlow, Scikit-learn, Transformers (BERT), CNN / LSTM, RAG, RAGAs |
| **Cloud & DevOps** | Docker, Kubernetes, Microsoft Azure, AWS, GitHub Actions, Linux / Bash, Git |

---

## Recognition

- 🥇 **CODE RED'25 Hackathon** — 4th place of 1,000+ teams
- 🏆 **ELCIA Next-Gen Tech Hackathon** — Top 10 finalist, 500+ teams
- 🎤 **Event Management Lead, GDSC-RVCE** — ran Tech Tank for 500+ students

---

## GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=prabujayant&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub Stats" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=prabujayant&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" height="165" />

<img src="https://github-readme-streak-stats.demolab.com?user=prabujayant&theme=tokyonight-night&hide_border=true" alt="GitHub Streak" />

<img src="https://github-profile-trophy.vercel.app/?username=prabujayant&theme=tokyonight&no-frame=true&row=2&column=7" alt="GitHub Trophies" />

</div>

---

## Connect

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:prabu.jayant2022@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/prabu-jayant-6b316b251/)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://prabujayant.vercel.app)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/prabujayant)

---

<div align="center">

**Thanks for visiting!**

</div>
