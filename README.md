<div align="center">

# Anandhasasidharan

### Cybersecurity × AI

**Building security systems for the age of AI agents.**

I build at the intersection of **cybersecurity, AI systems, agent security, and reliability** — with a bias toward infrastructure, adversarial testing, and explicit security guarantees.

[GitHub](https://github.com/Anandhasasidharan) · [Website](https://anandhasasidharan.github.io/xplorertech00.github.io/) · [LinkedIn](https://www.linkedin.com/in/asd01/) · [Blog](https://xplorertech00.wordpress.com/)

</div>

---

## What I Build

```text
CYBERSECURITY × AI
│
├── AI / Agent Security
│   ├── Prompt injection & tool abuse
│   ├── Agent identity & authorization
│   ├── Capability security & provenance
│   └── MCP security
│
├── Security Infrastructure
│   ├── Reference monitors
│   ├── Vulnerability scanning
│   ├── EDR / XDR for agents
│   ├── Security observability
│   └── Incident analysis
│
├── AI Reliability
│   ├── Failure attribution
│   ├── Chaos / resilience testing
│   ├── Evaluation systems
│   └── Runtime safeguards
│
└── AI Systems
    ├── LLMs & SLMs
    ├── Interpretability
    └── Local inference
```

## Featured Work

### 🛡️ [SENTRIX — EDR/XDR for AI Agents](https://github.com/Anandhasasidharan/SENTRIX)

Security architecture built around **prevention before detection**.

- Dual-LLM isolation with privileged and quarantined contexts
- Reference-monitor enforcement before tool execution
- Capability policies, provenance tracking, and least privilege
- Static taint analysis for agent/tool integrations
- Session replay, attack DAGs, and incident reports
- Adaptive attack harness with obfuscation and MCP-specific tests
- AgentDojo + AgentDyn evaluation

### 🔐 [AgentIAM — Identity & Access Management for AI Agents](https://github.com/Anandhasasidharan/AGENT-IAM)

Authorization infrastructure for systems where agents delegate work to other agents.

- Invocation-Bound Capability Tokens
- Chained Attenuation Tokens
- Scope narrowing across delegation hops
- Offline verification and revocation
- SPIFFE/SPIRE workload identity
- MCP OAuth 2.1 + PKCE
- SLSA-style provenance
- W3C Verifiable Credentials + A2A

> **Delegation may narrow authority — never expand it.**

### 📦 [AgentGOV — AI Agent Governance & AIBOMs](https://github.com/Anandhasasidharan/AgentGOV)

Infrastructure for answering: **what is an agent built from, and what is it allowed to do?**

- SPDX 3.0 AI Profile + CycloneDX ML-BOM v1.7
- Agent discovery and inventory
- Configuration drift detection
- OPA policy enforcement
- Identity / tool / data / model risk scoring
- EU AI Act, NIST AI RMF, and ISO 42001 crosswalks

### ⚙️ [AgentReflex — Agent Reliability Engineering](https://github.com/Anandhasasidharan/agent-reflex)

Treats agent failures as **causal systems problems**, not just log messages.

- OpenTelemetry-native instrumentation
- Causal graph reconstruction
- Counterfactual failure attribution
- MAST+ failure classification
- Contextual-bandit recovery selection
- Uncertainty-calibrated human escalation
- Reliability scoring and topology risk

### 🔎 [Community AI Audit](https://github.com/Anandhasasidharan/community-ai-audit)

Open-source AI/ML auditing platform combining security assessment, red teaming, interpretability, alignment checks, and unified risk scoring.

- Vulnerability scanning
- Red-team attack simulation
- Behavioral probes
- Mechanistic interpretability
- Alignment auditing
- 7-dimension risk scoring
- SIEM integrations
- CLI + REST API + Docker

### 🧪 [VulnGPT MCP Server](https://github.com/Anandhasasidharan/vulngpt-mcp-server)

Security tooling for MCP implementations: code vulnerabilities, dependency CVEs, hardcoded secrets, MCP flaws, and tool poisoning.

### 🧠 [ProbeKit](https://github.com/Anandhasasidharan/probekit-prism)

Interpretability infrastructure for activation harvesting, SAEs, cross-layer transcoders, attribution graphs, feature interpretation, steering, and drift monitoring.

### 🌐 [ORYTH — Personal Cyber Risk Dashboard](https://github.com/Anandhasasidharan/ORYTH)

Self-hosted monitoring for public attack-surface exposure, open ports, risk scoring, and breach signals.

### ⚛️ [Quantum Drone Pilot](https://github.com/Anandhasasidharan/quantum)

Interactive 3D exploration of quantum cryptography and attacks using Qiskit + Godot, including BB84 and Grover's algorithm.

---

## The Common Thread

Most of my recent work follows the same loop:

```text
       AI SYSTEM
           │
           ▼
      ┌──────────┐
      │ OBSERVE  │
      └────┬─────┘
           ▼
      ┌──────────┐
      │  ATTACK  │
      └────┬─────┘
           ▼
      ┌──────────┐
      │ MEASURE  │
      └────┬─────┘
           ▼
      ┌──────────┐
      │ ENFORCE  │
      └────┬─────┘
           ▼
      ┌──────────┐
      │  IMPROVE │
      └──────────┘
```

I'm especially interested in the layer **around** the model: identity, permissions, tool execution, telemetry, evaluation, failure handling, and security controls.

## Current Focus

- 🔐 Security architectures for AI agents
- 🧩 MCP and tool-use security
- 🪪 Agent identity, authorization, and delegation
- 🛡️ AI vulnerability assessment and red teaming
- 📡 AI observability and OpenTelemetry
- 🧪 Agent evaluation and reliability engineering
- 🧠 Mechanistic interpretability
- 💻 Local LLM inference and small-model experimentation

## Technical Stack

**Languages** — `Python` · `TypeScript` · `SQL` · `Bash`

**AI / ML** — `PyTorch` · `Hugging Face` · `Transformers` · `scikit-learn` · `Qiskit`

**AI Systems** — `LLMs` · `SLMs` · `Agents` · `MCP` · `OpenTelemetry` · `vLLM` · `llama.cpp`

**Security** — `Static Analysis` · `Taint Analysis` · `Red Teaming` · `IAM` · `OAuth` · `mTLS` · `Threat Modeling`

**Infrastructure** — `FastAPI` · `PostgreSQL` · `Redis/Valkey` · `Docker` · `Kubernetes` · `Terraform` · `GitHub Actions`

## Learning in Public

I build from first principles — from **neural networks and LLM internals** to the infrastructure required to deploy, observe, evaluate, and secure agentic systems.

Some projects are experimental. Some are research-adjacent. Some are production-oriented. I prefer making the work inspectable over pretending everything is finished.

## Selected Repositories

| Repository | Area |
|---|---|
| [SENTRIX](https://github.com/Anandhasasidharan/SENTRIX) | AI Agent Security / EDR-XDR |
| [AgentIAM](https://github.com/Anandhasasidharan/AGENT-IAM) | Agent Identity & Authorization |
| [AgentGOV](https://github.com/Anandhasasidharan/AgentGOV) | AI Governance / AIBOM |
| [AgentReflex](https://github.com/Anandhasasidharan/agent-reflex) | Agent Reliability |
| [Community AI Audit](https://github.com/Anandhasasidharan/community-ai-audit) | AI Security Auditing |
| [VulnGPT MCP](https://github.com/Anandhasasidharan/vulngpt-mcp-server) | MCP Security |
| [ProbeKit](https://github.com/Anandhasasidharan/probekit-prism) | Interpretability |
| [ORYTH](https://github.com/Anandhasasidharan/ORYTH) | Cyber Risk Monitoring |

---

<div align="center">

**Build it. Break it. Measure it. Secure it.**

</div>
