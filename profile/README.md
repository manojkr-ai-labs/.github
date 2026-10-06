# Manoj Kumar Sah

I build applied AI products: retrieval over real documents, agents that publish a result, and small web apps with a narrow job to do.

India · [manojkr6637@gmail.com](mailto:manojkr6637@gmail.com) · personal GitHub [@Manojkr6637](https://github.com/Manojkr6637)

**Live demo:** [AI Document Chat](https://ai-document-chat-rag-seven.vercel.app) — upload a PDF, ask questions, answers stay on that document.

## Selected work

Open these first. Forks in this org are reference copies, not my projects.

### Retrieval and agents

| Project | What it does | Where to look |
| --- | --- | --- |
| [AI Document Chat](https://github.com/manojkr-ai-labs/ai-document-chat-rag) | RAG API: upload PDFs, index them, chat with a local model. FastAPI, LangChain, ChromaDB, Ollama, Docker, GitHub Actions. | [Live app](https://ai-document-chat-rag-seven.vercel.app) |
| [Nike financial RAG agent](https://github.com/manojkr-ai-labs/nike-financial-rag-agent) | Grounded Q&A over financial documents. n8n, Ollama, Pinecone, Qwen3. | Repo |
| [Groww review intelligence](https://github.com/manojkr-ai-labs/grow-review-aiagent-mcp) | Weekly Play Store review pulse. Publishes through MCP to Google Docs and Gmail. | Repo |
| [Customer summary emails](https://github.com/manojkr-ai-labs/ai-customer-summary-email-automation) | Turns customer context into a summary and an email. n8n, OpenAI, Google Sheets, Gmail. | Repo |

### Product apps

| Project | What it does | Where to look |
| --- | --- | --- |
| [BiteRank](https://github.com/manojkr-ai-labs/zomato-restaurant-recommendation) | Restaurant recommendations: filter a real dataset, then a Groq model ranks and explains the fit. FastAPI + Next.js. | Repo |
| [InterviewGap](https://github.com/manojkr-ai-labs/interviewgap) | One resume + one job description → fit score, quote-backed gaps, 7-day plan, scored mock interview. HackerEarth AI Innovation Arena, Oct 2026. | [Open the demo](https://manojkr-ai-labs.github.io/interviewgap/) |

## How I build

- Answers come from a corpus (a PDF, a fund FAQ, a resume the user pasted), not from a model guessing.
- Local models where the data should stay on the machine (Ollama), hosted models where a demo needs to be public (Groq, OpenAI).
- A thin product around the model: API, UI, export, or a scheduled workflow — not a notebook screenshot.
- Shipping surface called out in the repo: Docker and CI on Document Chat, Railway + Vercel plans on BiteRank.

## Stack

Python · FastAPI · LangChain · CrewAI · ChromaDB · Pinecone · Ollama · n8n · Next.js · Docker · MCP
