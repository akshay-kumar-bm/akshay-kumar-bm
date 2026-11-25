<div align="center">

# Akshay Kumar BM

**Senior AI Engineer** · Production AI agents, MCP servers & evals

[![Portfolio](https://img.shields.io/badge/Case_studies-akshaykumarbm.tech-0f6e57?style=flat)](https://www.akshaykumarbm.tech)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-akshay--kumar--bm-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/akshay-kumar-bm)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=flat&logo=gmail)](mailto:akshaykumarbedre.bm@gmail.com)

</div>

---

I build AI agents that run in production, not just in demos. Three of my agents run in production for a Fortune 500 pharmaceutical client's SRE team:

- **Observability Copilot**: plain-English questions over Grafana, Loki and Prometheus through a custom MCP server I wrote. One of the top 10 most-used tools across the SRE team.
- **Anomaly Watch agent**: monitors production logs continuously. 72% of what it flags is a confirmed production issue.
- **Alert RCA agent**: starts when a Grafana alert fires, reads the logs and metrics, and posts the likely root cause.

I also deployed and run **Langfuse** for these agents: every run is traced, success and failure rates are tracked, and LLM-as-judge evaluators check the output.

The work I care about is the layer around the model: the tools it can reach, the access it's given, the human checkpoints and the evals that prove it still works.

## Open source

| Project | What it does |
|---|---|
| [**prosper-voice-windows**](https://github.com/shipengineai/prosper-voice-windows) | Voice dictation and an AI assistant for any Windows app: speak to type, edit selected text by voice, add the screen as context, MCP tools with per-call approval. Runs for about $1–1.5 a month in API costs. |
| [**Omnigate**](https://github.com/akshay-kumar-bm/omnigate) | One remote MCP server for any HTTP API. Every common auth scheme is handled server-side, so agents never see a credential. Multi-step workflows run in a single tool call, with per-host allowlists and human approval for destructive calls. |
| [**rl-scheduling-env**](https://github.com/akshay-kumar-bm/rl-scheduling-env) | OpenEnv RL environment for meeting scheduling. Meta PyTorch OpenEnv Hackathon, Top 100 of 31,000+. |
| [**invoice-extraction-pro**](https://github.com/akshay-kumar-bm/invoice-extraction-pro) | Multimodal invoice and document extraction (10 min → under 1 min per document). |

## Stack

**Agents:** Claude Agent SDK · MCP · LangGraph · LangChain · multi-agent pipelines
**Evals:** LLM-as-judge · regression suites · Langfuse tracing
**Retrieval:** RAG · FAISS · Chroma
**Observability:** Grafana · Loki · Prometheus · Jaeger
**Platform:** Python · FastAPI · Docker · Kubernetes · AWS · GCP · GitHub Actions

## Recognition

- 1st place, AMD AI Sprint 2025 at IISc
- Top 100 of 31,000+, Meta PyTorch OpenEnv Hackathon
- Participant, Guinness World Record agentic AI hackathon (Google Cloud × Hack2skill)

<sub>Bengaluru, India · I write about MCP, evals and agent guardrails on LinkedIn.</sub>
