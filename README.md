👋 Hi — I’m Kenedy Kabori Richard

> Founder & CTO at KORIVA — Building open financial infrastructure (payments, identity, compliance, APIs) for African markets.

[![Last Commit](https://img.shields.io/github/last-commit/TorDrc/TorDrc)](https://github.com/TorDrc/TorDrc/commits)
[![Repo Size](https://img.shields.io/github/repo-size/TorDrc/TorDrc)](https://github.com/TorDrc/TorDrc)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/TorDrc/TorDrc/blob/main/LICENSE)
[![Open issues](https://img.shields.io/github/issues/TorDrc/TorDrc)](https://github.com/TorDrc/TorDrc/issues)
[![Open PRs](https://img.shields.io/github/issues-pr/TorDrc/TorDrc)](https://github.com/TorDrc/TorDrc/pulls)

---

# KORIVA — Financial Infrastructure for Africa

KORIVA is an infrastructure and interoperability platform designed to connect fragmented financial ecosystems through a unified technology layer.

Core focus areas

- 💳 Payments & Transfers
- 🪪 Identity & KYC
- 🛡️ Compliance & Risk
- 🔌 Financial APIs
- 💰 Wallets & Accounts
- 📒 Financial Ledger
- 🌍 Cross-border Infrastructure
- 🤖 AI & Automation
- ⛓️ Blockchain & Digital Assets

The long-term goal is to make it easier for financial institutions, fintechs, businesses, and digital platforms to connect to financial services through standardized, secure APIs.

---

## Table of Contents

- [What I’m Building](#what-im-building)
- [Architecture (ASCII)](#architecture-ascii)
- [Technology & Areas](#technology--areas)
  - [Backend](#backend)
  - [Database & Infrastructure](#database--infrastructure)
- [Other Projects](#other-projects)
- [Current Focus](#current-focus)
- [Vision](#vision)
- [Engineering Principles](#engineering-principles)
- [Featured Projects](#featured-projects)
- [Open to](#open-to)
- [Connect](#connect)

---

## What I’m Building

KORIVA — Financial Infrastructure

## Architecture (ASCII)

```text
                 KORIVA API

    Identity    │   Payments   │  Compliance
        │              │            │
    Wallets       Ledger        Transfers

Financial Ecosystem → standardized APIs & integrations
```

---

## Technology & Areas

### Backend

I build the backend with reliability, security, and auditability in mind. Common concerns and components include:

- API-first services (REST/JSON) with clear versioning
- Authentication & authorization (OAuth2 / JWT / mTLS where applicable)
- Microservice or modular monolith approaches depending on domain boundaries
- Observability: structured logging, distributed tracing, metrics (Prometheus/Grafana)
- Automated testing (unit/integration) and CI pipelines

### Database & Infrastructure

Core infrastructure patterns and choices:

- Relational ledgers (Postgres / ACID-compliant systems) for financial state
- Append-only accounting or event-sourced ledgers where appropriate
- Caching (Redis) and queueing (Kafka / RabbitMQ) for throughput and decoupling
- Cloud-native deployment (containers, Kubernetes, IaC like Terraform)
- Secure key management (KMS / HSM) and secrets handling
- Regular backups, point-in-time recovery, and DR planning

---

## Other Projects

- **KORIVADASHBOARD** — Web/dashboard for KORIVA (https://github.com/TorDrc/KORIVADASHBOARD)
- **richy-hunter-ai** — AI-powered Solana market intelligence (https://github.com/TorDrc/richy-hunter-ai)
- **richy-hunter-ai-dashboard** — Dashboard for Richy Hunter AI (https://github.com/TorDrc/richy-hunter-ai-dashboard)

---

## Current Focus

- KORIVA Infrastructure
  - API Architecture
  - Financial Core
  - Ledger
  - Identity & Compliance
  - Payment Infrastructure
  - Security
  - Cloud Infrastructure
  - Developer APIs

---

## Vision

Africa has a rapidly growing digital financial ecosystem, but many financial systems remain fragmented across banks, mobile-money networks, fintech platforms, payment processors, and digital assets. KORIVA is being built around the idea that interoperability should become infrastructure — a technology layer that allows different financial systems to communicate through standardized, secure APIs.

---

## Engineering Principles

I focus on building systems around:

- Security first
- API-first architecture
- Interoperability
- Scalability
- Auditability
- Reliability
- Developer experience
- Financial data integrity

For financial infrastructure, correctness and security matter more than simply shipping features quickly.

---

## Featured Projects

- [KORIVA (project)](https://github.com/TorDrc/KORIVADASHBOARD) — Financial infrastructure and interoperability
- [KORIVADASHBOARD](https://github.com/TorDrc/KORIVADASHBOARD) — KORIVA web/dashboard infrastructure
- [Richy Hunter AI](https://github.com/TorDrc/richy-hunter-ai) — AI & blockchain market intelligence

---

## Open to

I’m interested in connecting with:

- Fintech builders
- Software engineers
- Financial institutions
- Payment companies
- API providers
- Blockchain developers
- AI engineers
- African technology entrepreneurs
- Potential strategic partners

If you’re working on financial infrastructure, interoperability, payments, AI, or blockchain in Africa, I’d be interested in connecting.

---

## Connect

- GitHub: https://github.com/TorDrc
- Email: kenedykabori104@gmail.com

(If you prefer only GitHub exposure, I can remove the email and keep GitHub only — tell me.)

---

> Building KORIVA, one layer at a time.

Infrastructure before interfaces. Security before scale. Interoperability by design.
