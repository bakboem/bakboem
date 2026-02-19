
# 👋 Hi, I’m 白帆 (bakboem)

Solo Founder · CEO & CTO  
Full-stack engineer & infrastructure architect based in Korea.

I run a **one-person software company** building **stateful matching systems**,  
**event-driven backends**, and **fully reproducible infrastructure** — end to end.

I don’t build feeds.  
I don’t build generic communities.  
I build systems that can **freeze a moment, make a decision, and explain it**.

---

## 🧭 What I’m Building

### **WorkFit — A Real-Time Need Verification & Matching Engine**

WorkFit is a matching-first platform for foreigners in Korea.

It is **not** a social timeline.  
It is a system designed around **ephemeral needs** and **repeatable judgment**.

Core principles:

- Needs are **time-bounded and state-frozen**
- Each match is a **single, explainable decision**
- No long-term personality profiling
- No hidden preference inference
- Every outcome is **replayable, inspectable, and auditable**

What the system is optimized for:

- High-concurrency matching under constrained time windows
- Event-driven pipelines (Kafka / NATS)
- Deterministic scoring with full explainability
- WebSocket-based feedback and intent loops
- Multilingual runtime (CN / KR / EN)

This is the **core product** and the system I am actively operating and stress-testing.

---

## 🏗 Infrastructure Philosophy

I operate **enterprise-grade infrastructure as a one-person company**.

Design rules:

- Full automation
- No hidden state
- No environment drift
- Production ≈ Local

Current architecture highlights:

- AWS single-server architecture (t4g + Docker Compose)
- PostgreSQL 18 (self-built, full control, no managed DB)
- Kafka (KRaft) + NATS as the event backbone
- Prometheus / Loki / Grafana as a separate observability plane
- GitHub Actions → ECR → reproducible deployments
- Local / test / prod with **100% configuration parity**

Goal:

> **Maximum system clarity with minimum operational surface area.**

---

## 🧠 What I Care About

- Matching systems under real-world constraints
- Explainable, replayable decision pipelines
- Event-driven architectures that don’t lie
- Stateful systems that respect time and causality
- Multilingual platforms with real operational depth

I’m especially interested in systems where:

> *Every result must be defensible.*

---

## 🛠 Tech Stack (Current)

**Backend**
- Go
- PostgreSQL 18
- Kafka (KRaft)
- NATS
- Redis / ElastiCache

**Infrastructure**
- AWS (EC2, EBS, ECR)
- Terraform
- GitHub Actions
- Docker Compose
- Make / Bash automation

**Observability**
- Fluent Bit
- Loki
- Prometheus Agent
- Grafana

**Frontend**
- Next.js (App Router, SSR)
- Multilingual routing

**AI (Selective, Non-Magical)**
- OpenAI API
- Structured workflows
- Agent integration as tooling, not decision authority

---

## 🤝 Open to Conversations About

- Matching engines
- Event-driven systems
- Explainability-first architectures
- Agent-assisted (not agent-controlled) products
- DSL-based world or rule systems

---

## ⚡ Personal Note

I don’t chase trends.  
I build systems that can survive **being questioned**.

WorkFit is my answer to:

> *“What if software decisions had to be honest?”*

