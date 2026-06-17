# 🤖 LoanDt AI Agent

[![GitHub license](https://img.shields.io/github/license/Loandt1978/LoanDt)](https://github.com/Loandt1978/LoanDt/blob/master/LICENSE)
[![Framework](https://img.shields.io/badge/Framework-OpenClaw-blue)](https://docs.openclaw.ai)
[![Infrastructure](https://img.shields.io/badge/Infra-GreenNode-green)](https://greennode.ai)

Welcome to the repository of **LoanDt AI Agent** — a specialized AI entity designed not just to chat, but to execute, manage, and advise. 

This agent is built on the **OpenClaw** framework and powered by **GreenNode AgentBase**, combining deep domain knowledge with cloud-native execution capabilities.

---

## 🌟 Core Philosophy (The Soul)

Unlike traditional chatbots, LoanDt AI is designed with a "Soul" (`SOUL.md`). It operates on three fundamental pillars:
*   **Genuine Helpfulness:** No performative filler words. It focuses on concrete actions and accurate answers.
*   **Resourcefulness:** It is trained to explore, read, and synthesize information before asking for help.
*   **Competence-Based Trust:** It earns trust through precision in legal advisory and technical execution.

---

## 🚀 Capabilities

### ⚖️ Specialized Domain Expertise
The agent has been fine-tuned/instructed to provide high-accuracy guidance on:
- **Vietnam Health Insurance (BHYT):** Policies, "Thông tuyến" (network synchronization), and benefit calculations.
- **Labor Law & Employment:** Legal frameworks, contract disputes, and worker rights.
- **Unemployment Insurance:** Eligibility, calculation of benefits, and filing procedures.

### 🛠️ Technical Infrastructure Orchestration
Integrated with the **GreenNode AgentBase Skill-set**, the agent can autonomously manage its own lifecycle:
- **Scaffolding:** `/agentbase-wizard` to initialize new agent projects.
- **Deployment:** `/agentbase-deploy` to build, push Docker images, and deploy to Custom Agent runtimes.
- **Monitoring:** `/agentbase-monitor` for real-time logs, CPU/RAM metrics, and health checks.
- **Security:** `/agentbase-policy` & `/agentbase-gateway` to manage IAM policies and MCP gateways.

---

## 🛠 Technical Stack

- **Orchestration:** [OpenClaw](https://openclaw.ai)
- **Runtime Infrastructure:** GreenNode Platform
- **Memory System:** Semantic Long-term Memory (`MEMORY.md`) + Daily Session Logs.
- **Skills Engine:** `SKILL.md` compatible procedures (Bash/Curl/Markdown).

---

## 📋 Skill-Set Matrix

| Command | Action | Description |
| :--- | :--- | :--- |
| `/agentbase-wizard` | **Lifecycle** | Guided path from `init` $\rightarrow$ `test` $\rightarrow$ `deploy`. |
| `/agentbase-deploy` | **Ops** | Manages Container Registry & Runtime deployments. |
| `/agentbase-llm` | **Config** | Manages platform LLM API keys and model catalogs. |
| `/agentbase-memory` | **Cognition** | Manages long-term semantic memory stores. |
| `/agentbase-monitor` | **Observe** | Fetches runtime logs and endpoint metrics. |
| `/agentbase-gateway` | **Network** | Configures Resource Gateways and outbound auth. |
| `/agentbase-teardown`| **Cleanup** | Safe deletion of all project resources. |

---

## 🚀 Quick Start

### 1. Prerequisites
Ensure you have your GreenNode IAM credentials set:
```bash
export GREENNODE_CLIENT_ID="your-client-id"
export GREENNODE_CLIENT_SECRET="your-client-secret"
```

### 2. Deployment
To deploy a similar agent based on this configuration:
1. Clone this repo.
2. Run the wizard: `/agentbase-wizard init <agent-name>`
3. Deploy: `/agentbase-deploy deploy`

---

## 📂 Repository Structure
- `/` : Core Agent Identity (`SOUL.md`, `USER.md`, `IDENTITY.md`).
- `/greennode-agentbase-skills/` : The complete set of execution skills for the GreenNode platform.
- `/memory/` : (Ignored) Daily session context and learning logs.

---
*Designed for efficiency, built for execution.*
