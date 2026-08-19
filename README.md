# PARAM-ship

### Building systems. Exploring ideas. Shipping things.

PARAM-ship is an engineering organization for building and experimenting with software across **AI, backend systems, developer tooling, infrastructure, and financial technology**.

We build projects to understand how things actually work — from multi-agent LLM systems and code-review pipelines to exchange infrastructure and developer tools.

> **Build → Understand → Break → Improve → Ship**

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🧠 Nexus

**Multi-Agent Code Review Pipeline**

Nexus uses parallel specialist agents to review pull requests and a dedicated **critic agent** to verify findings before they reach the developer.

The goal isn't simply to make an LLM review code.

It's to make the system **less likely to confidently hallucinate problems**.

**Stack**

`TypeScript` `Bun` `Groq` `Llama 3.3 70B`

**Highlights**

- Parallel specialist reviewers
- Critic / verification layer
- Structured findings
- Hallucination mitigation
- PR-oriented workflow
- Agent orchestration built from scratch

[→ Explore Nexus](https://github.com/PARAM-ship/nexus-review)

</td>

<td width="50%" valign="top">

### 💱 Exchange

**Centralized Crypto Exchange**

An experimental implementation of a centralized cryptocurrency exchange.

The project explores the systems behind an exchange — order processing, matching, accounts, balances, APIs, and the infrastructure required to build a reliable financial system.

**Stack**

`TypeScript` `Bun`

**Focus**

- Trading infrastructure
- Order matching
- Backend architecture
- Financial state management
- Concurrency
- Distributed systems

[→ Explore Exchange](https://github.com/PARAM-ship/exchange)

</td>
</tr>
</table>

---

## 📦 Projects

| Project | Description | Technologies |
| --- | --- | --- |
| 🧠 [Nexus](https://github.com/PARAM-ship/nexus-review) | Multi-agent code review with critic-based verification | TypeScript · Bun · Groq |
| 💱 [Exchange](https://github.com/PARAM-ship/exchange) | Centralized exchange engineering project | TypeScript · Bun |
| 🐝 [Hubble](https://github.com/PARAM-ship/homebrew-hubble) | Homebrew distribution for Hubble | Homebrew |
| 💳 [Paytm Mini](https://github.com/PARAM-ship/paytm-mini) | Payment-system engineering experiment | — |

---

# 🧠 What We're Exploring

PARAM-ship sits at the intersection of several areas of software engineering.

### Artificial Intelligence

- LLM applications
- AI agents
- Multi-agent systems
- RAG systems
- Agent orchestration
- Evaluation
- Guardrails
- AI developer tools
- LLM reliability

### Backend & Systems

- API design
- Distributed systems
- Concurrency
- Databases
- Message queues
- Caching
- Event-driven architecture
- Fault tolerance
- Observability

### Developer Infrastructure

- Developer tooling
- CLI applications
- Build systems
- Package distribution
- Automation
- CI/CD
- Infrastructure

### Financial Technology

- Exchanges
- Order books
- Matching engines
- Payments
- Ledger systems
- Transaction processing
- Financial state machines

---

# 🏗️ Engineering Philosophy

We don't want to just make things work.

We want to understand **why they work**.

### 01 — First Principles

Start with the underlying problem before reaching for a framework.

### 02 — Build From Scratch

When practical, implement the core mechanism ourselves before hiding it behind an abstraction.

### 03 — Make Failure Visible

Systems should make incorrect behavior observable instead of silently producing plausible results.

### 04 — Prefer Simple Architecture

Complexity should be earned.

### 05 — Measure, Don't Assume

Benchmarks, tests, evaluations, logs, and metrics beat intuition.

### 06 — Ship

A working system teaches more than an unfinished idea.

---

# 🔬 Experiments

Not every repository here is intended to become a production product.

Some exist because the best way to understand a system is to **build one**.

That means you'll find:

- prototypes
- experiments
- infrastructure projects
- AI systems
- developer tools
- deliberately small implementations
- projects exploring architectural ideas

Some will evolve.

Some will be rewritten.

Some will be abandoned.

That's part of the process.

---

# 🛠️ Technology

Our stack changes with the problem.

Some technologies we work with include:

<p>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/Bun-000000?style=for-the-badge&logo=bun&logoColor=white" />
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
</p>

<p>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" />
</p>

<p>
<img src="https://img.shields.io/badge/LLMs-111111?style=for-the-badge&logo=openai&logoColor=white" />
<img src="https://img.shields.io/badge/RAG-111111?style=for-the-badge&logo=googlecloud&logoColor=white" />
<img src="https://img.shields.io/badge/AI_Agents-111111?style=for-the-badge&logo=probot&logoColor=white" />
</p>

---

# 📚 What We're Learning

Building is only half of the process.

We continuously explore the concepts underneath the systems we build:

```text
Algorithms
    ↓
Data Structures
    ↓
Operating Systems
    ↓
Networking
    ↓
Databases
    ↓
Distributed Systems
    ↓
Backend Architecture
    ↓
AI / ML Systems
    ↓
Production Infrastructure
