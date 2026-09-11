# Hi, I'm Bashiir 👋

**AI Engineer & Software Engineer.** I build AI agents and full-stack products that are measured, tested and safe to run: evaluated in CI, grounded in cited sources, and built to degrade gracefully instead of crashing.

## Featured projects

### 🔎 [Tarjouspyyntötutka](https://github.com/bashiir-code/tarjouspyyntotutka): AI agent for Finnish public procurement
An agent that reads Finnish public tender notices (HILMA) and answers questions in Finnish, with citations and a fit assessment for a company's profile.
- Hybrid search reached **93 % recall@5** on a 30-question eval, against 77–80 % for vector search alone.
- Search filters are enforced in code, and every citation is checked against the retrieved notices. The eval runs in CI.

`Python` `FastAPI` `Azure AI Search` `Foundry Agent Service` `React` `TypeScript` `Bicep`

### 🧠 [SSI Blog Agent](https://github.com/bashiir-code/ssi_trustgraph): multi-agent research pipeline
A LangGraph system that turns member questions into a fact-checked market report with numbered sources.
- Specialist agents, a critic that sends research back for another round, a validator, and an analyst/writer pair.
- It has retry/fallback, a cost budget and a prompt-injection guard, and runs end to end in CI with no API keys.

`Python` `LangGraph` `Pydantic` `DeepSeek` `Supabase` `Redis` `GitHub Actions`

### ⚖️ [SME AI Auditor](https://github.com/bashiir-code/sme_ai_auditor): EU AI Act compliance tool
It reads an AI system's documentation and produces a compliance report under the EU AI Act and Data Act, covering risk tier, legal gaps and a remediation plan.
- Mistral does the legal reasoning, a Qwen agent drives the audit through an MCP server, and every step is traced in Langfuse.

`Python` `Haystack` `Mistral` `MCP` `Qdrant` `Docling` `FastAPI` `HTMX`

### 🏠 [Guri](https://github.com/bashiir-code/guri): rental marketplace (full-stack)
A mobile-first PWA for renting homes in Mogadishu, where every listing is tied to a verified agency. It ran in production as a pilot.
- About 21,000 lines of strict TypeScript, with 104 API tests that must pass before every deploy.
- Five server-checked roles, a state machine for deals, an audit log, and Somali + English.

`TypeScript` `Next.js` `NestJS` `Prisma` `PostgreSQL`

### 🚦 [Nordic Asphalt Pulse](https://github.com/bashiir-code/Nordic-Asphalt-Pulse-Enterprise-Data-Lakehouse-on-Databricks): traffic and weather data lakehouse
A Databricks medallion lakehouse that joins live Finnish road-sensor data with weather for 50 cities. It uses geospatial matching to label each traffic jam as weather-caused or volume-caused.

`Databricks` `Delta Lake` `PySpark` `SQL`

### 🎮 [Clash Royale AI Coach](https://github.com/bashiir-code/game_AI_hackathon_2026): hackathon, 4-person team
A local AI coach that watches the game screen and gives spoken tactical advice. I worked on the architecture and wrote the setup instructions for the team.

`Python` `Ollama` `OpenCV`

## Tech I work with

**AI & data:** LangGraph · RAG · MCP · Azure AI Search · Qdrant · Pydantic · evals in CI · Databricks · PySpark
**Backend:** Python · FastAPI · NestJS · PostgreSQL · Prisma · Supabase · Redis
**Frontend:** TypeScript · React · Next.js · Tailwind
**Delivery:** GitHub Actions · Bicep · Docker
