# LegalBrief AI

**LegalBrief AI** is a full-stack legal document intelligence platform. It uses AI agents to extract summaries, flag contractual risks, and enable rapid analysis of dense legal contracts.

---

## 🔍 Features
- Upload and parse legal documents (PDF)
- Summarize documents using LLMs (OpenAI, Claude, etc.)
- Flag risky clauses with autonomous AI agents
- Retrieval-augmented generation (RAG) from precedent databases
- Modular architecture with gRPC-based multi-agent system

---

## 🧱 Tech Stack
| Layer      | Technology                         |
|------------|-------------------------------------|
| Frontend   | React + Vite                        |
| Backend    | Node.js + Express                   |
| AI Agents  | Python + gRPC, LangChain/CrewAI     |
| Storage    | PostgreSQL (future), Vector DB      |
| Deployment | Docker + Docker Compose             |

---

## 🚀 Quick Start
```bash
# Start all services
$ docker-compose up --build
```

## 📁 Project Structure
```bash
backend/         # Node.js REST API
frontend/        # React frontend
ai_agents/       # Python gRPC services
```

## 🧠 Roadmap
- [ ] Upload and parse contracts
- [ ] Summarization agent (LLM)
- [ ] Risk assessment agent (crew-based)
- [ ] User auth + history
- [ ] PDF highlighting in UI

## 📄 License
MIT

---
Made with 🧠 by Zain Mathews