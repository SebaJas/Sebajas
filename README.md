## Hi there 👋 I'm Sebastian Alvarez
**Senior Software Engineer** based in Argentina 🇦🇷, working remotely with US companies since 2019.


📊 **About My Contribution Graph**

If you're wondering about my contribution activity — most of my daily coding happens in a **separate work GitHub account** (private company repos). What you see here are my personal projects and open-source work.


🔧 **By day:** Senior Software Engineer at **SWARM Engineering** (via ClickIT), working on a multi-tenant enterprise AI + optimization SaaS — Go microservices, multi-tenant SSO / identity, and GitOps-based Kubernetes delivery. Also with **Cognativ Inc.**, building real-time video analytics engines with Go, Kafka, and AWS IoT Core.

🎵 **By night:** Creator of VinilHub, Argentina's first vinyl marketplace.

─────────────────────────────────────────────────────────────────

🚀 **What I Do**

I build production distributed systems at scale with 8+ years of experience. My expertise lies in:


→ **Distributed Architectures** using CQRS, DDD, hexagonal, and event-driven design

→ **Real-time Systems** processing high-throughput IoT events with sub-100ms latency

→ **Multi-tenant SaaS** with tenant isolation, SSO / identity (Okta OIDC/SAML), and per-client feature flags

→ **Platform & Delivery** with Kubernetes and GitOps (Flux CD), plus incremental architecture consolidation

→ **Full-stack Development** from backend APIs to React/Next.js frontends

─────────────────────────────────────────────────────────────────

🛠️ **Tech Stack**

**Languages**

Go (primary) • TypeScript • Python • SQL

**Backend & Architecture**

Fiber • Gin • NestJS • Django • CQRS • DDD • Hexagonal Architecture • Microservices • Multi-tenancy

**Databases & Messaging**

PostgreSQL (expert) • Couchbase • MySQL • MSSQL • DynamoDB • Redis • Kafka • NSQ

**Identity & Auth**

Okta (OIDC/SAML) • JWE • JWT • RBAC

**Cloud & DevOps**

AWS (S3, Lambda, IoT Core, EC2, SNS, SQS) • Azure Key Vault • Docker • Kubernetes • Flux CD (GitOps) • GitHub Actions

**Frontend**

React • Next.js • Vue (single-spa micro-frontends) • Tailwind CSS • Zustand

─────────────────────────────────────────────────────────────────

⚡ **Key Achievements**

|            Project              |                                                        Description                                                                                             |
|---------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Real-Time Analytics Engine**  | Architected a video analytics engine in Go processing IoT events with sub-100ms latency, integrated with AWS IoT Core and Kafka                                |
| **Architecture Consolidation**  | Drove an incremental, stabilize-first (Strangler-Fig) effort to reduce microservice sprawl on an enterprise AI + optimization SaaS                             | 
| **Multi-Tenant SSO Redesign**   | Mapped the org-provisioning, registry, and SAML/JIT-routing flow end-to-end and produced the durable-fix design and scoped implementation tickets              |
| **Tenant Isolation Fix**        | Implemented tenant-scoped processing to close a cross-tenant data-exposure class in a notification pipeline (login → NSQ → Python service → Couchbase gateway) |
| **VinilHub Marketplace**        | Built Argentina's first vinyl marketplace — complete e-commerce with 3 payment providers (MercadoPago, Rebill, PayPal)                                         |
| **Subscription Billing System** | Designed billing handling 4 plan tiers with trials, proration, grace periods, and webhook processing                                                           |
| **CI/CD Pipelines**             | Established pipelines with Buildkite, Jenkins, and GitHub Actions across multiple production projects                                                          |

─────────────────────────────────────────────────────────────────

🎵 **Featured Project: VinilHub**

Argentina's first specialized vinyl marketplace connecting record stores, collectors, and buyers.

**Architecture Highlights:**

🏗️ Next.js 15 monorepo with 3 apps sharing UI library via Turborepo

⚙️ NestJS backend with TypeORM, PostgreSQL, clean layered architecture

🔐 JWT auth with HTTP-only cookies, refresh token rotation, RBAC

💳 Strategy Pattern for multiple payment providers with webhooks

📈 React Server Components, ISR, connection pooling for performance
