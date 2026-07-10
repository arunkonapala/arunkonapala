# Hi, I'm Arun Konapala 👋

**Lead AI / GenAI Platform Engineer** — 20 years of enterprise engineering, currently architecting agentic AI platforms, LLM evaluation frameworks, and MCP-integrated GenAI systems on AWS at Fannie Mae.

I work at the intersection of **agentic AI** (multi-agent orchestration, tool use, MCP), **AI platform engineering** (observability, evaluation, cost attribution), and **full-stack delivery** (Python/FastAPI backends, Angular frontends).

🌐 Portfolio & resume: **[arunkonapala.github.io](https://arunkonapala.github.io)** · 💼 [LinkedIn](https://linkedin.com/in/arunkonapala)

## Featured projects

| Project | What it is | Stack |
|---|---|---|
| [fraud-triage-agent](https://github.com/arunkonapala/fraud-triage-agent) | Agentic fraud triage — deterministic rules gate a LangGraph Claude investigator that tool-calls over the customer ledger and drafts SAR narratives with structured verdicts | LangGraph · Claude · FastAPI · Pydantic |
| [agent-observability](https://github.com/arunkonapala/agent-observability) | OTel observability layer for agent loops — spans per turn/tool/LLM call with token + USD cost attribution (GenAI semconv); traces fraud-triage-agent and finance-copilot, Jaeger screenshot in README | OpenTelemetry · LangChain · Jaeger |
| [llm-eval-harness](https://github.com/arunkonapala/llm-eval-harness) | LLM evaluation harness — DeepEval metric suite (relevancy, correctness, bias, toxicity, hallucination) over configurable judge/candidate models with consolidated pass/fail reporting | DeepEval · Python · Bedrock · Flask |
| [finance-mcp-server](https://github.com/arunkonapala/finance-mcp-server) | MCP server exposing 8 personal-finance tools to any MCP client (Claude Desktop, Claude Code, custom agents) | MCP · FastMCP · Python |
| [finance-copilot](https://github.com/arunkonapala/finance-copilot) | Conversational personal-finance assistant — **[live demo](https://finance-copilot-jito.onrender.com)** — streaming agentic tool-use loop, 8 finance tools, SSE to an Angular chat UI, provider-pluggable backend | Python · FastAPI · Claude · Angular |
| [financial-doc-qa-rag](https://github.com/arunkonapala/financial-doc-qa-rag) | RAG over annual reports & SEC filings with page-level citations | LangChain · FAISS · Cohere · Claude · AWS S3 |
| [healthcare-multiagent-chatbot](https://github.com/arunkonapala/healthcare-multiagent-chatbot) | Multi-agent healthcare consultation chatbot (AutoMed) | AG2 (AutoGen) · Claude |
| [crewai-meal-grocery-planner](https://github.com/arunkonapala/crewai-meal-grocery-planner) | Five-agent meal & grocery planner with structured outputs | CrewAI · Pydantic · YAML |
| [ai-nutrition-coach](https://github.com/arunkonapala/ai-nutrition-coach) | Meal-photo analysis with vision agents | Claude Vision · FastAPI · Angular 20 |

## Toolbox

**GenAI:** AWS Bedrock · AgentCore · MCP · Claude · LangChain · LangGraph · CrewAI · AutoGen (AG2) · RAG · Vector DBs (FAISS, Chroma, pgvector)
**Platform:** Python · FastAPI · Angular · TypeScript · Java · AWS (Lambda, ECS, Step Functions, SQS/SNS) · Terraform · OpenTelemetry
**Certifications:** 10× IBM AI & GenAI (2025) · AWS GenAI (2025) · Databricks GenAI Fundamentals (2025)
