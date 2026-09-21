# Hi, I'm Gabriel Bressan

**Senior AI Engineer · Data engineering · Software development**

I build AI products and the data systems behind them. Over nine years, my work has grown from BI and analytics into data engineering and production AI. I own the work from architecture and implementation through deployment and operations.

At Talentify, I build conversational analytics, recruitment software, and the pipelines that connect them. My work includes:

- Taking conversational analytics from prototype to production, reducing the time to answer business questions from three hours to ten minutes.
- Building nearly all of a recruitment advertising platform used by close to 100 people, tracking more than US$300K in media spend in August 2026.
- Building a BigQuery and Python data platform supporting 645 million rows, with integrations across operational databases and external APIs.
- Creating AI agents with provider fallback, evaluation, tracing, and tool access through MCP.

I care about what happens after the first successful demo: stale data, failed API calls, misleading answers, inference costs, and whether someone can trace a result back to its source.

## Selected projects

### Penzia

I built Penzia, owning the product, architecture, application, integrations, and deployment. It's a conversational AI platform for clinics, with separate React frontends for clients and admins, a Convex platform backend, and WhatsApp Business and Instagram messaging integrations. A separate AI service built with Agno and FastAPI coordinates specialist AI agents and handoff to human staff. Google Calendar integration lets agents check availability, book, reschedule, and cancel appointments. Configurable permissions support autonomous scheduling or supervised workflows that require human approval before calendar changes. Vision models read images and scanned or digital PDFs, while audio transcription brings voice notes into the conversation.

The platform tracks model usage and estimated costs by client and channel. I work on model selection and prompt caching, keeping changing context out of stable prompt prefixes. I also manage self-hosted infrastructure with Dokploy, Redis, PostgreSQL, Convex, and MinIO, with Grafana for infrastructure observability and Braintrust for AI agent observability.

`React` · `TypeScript` · `Convex` · `Agno` · `FastAPI` · `WhatsApp Business API` · `Instagram API` · `Google Calendar API` · `Vision models`

### [Recibo](https://github.com/gabrielsntr/recibo-capstone-ai-databricks)

A public-spending analysis project built on Databricks. It processes 1.47 million Brazilian parliamentary reimbursement records, reads receipt scans with vision models, and lets an agent investigate discrepancies. The most useful lesson was checking false positives against the original receipts, including cases where two models agreed and both were wrong.

`Python` · `Spark` · `Delta Lake` · `Unity Catalog` · `Vector Search` · `Streamlit`

### [Weather MCP + Agent Bricks](https://github.com/gabrielsntr/weather-mcp-server-agent-bricks)

A weather agent backed by eight MCP tools, with a dashboard for checking its calls. It uses live weather sources, explicit error responses, and explainable recommendation rules so the agent can distinguish missing data from an actual forecast.

`FastMCP` · `FastAPI` · `Databricks Apps` · `Agent Bricks` · `Lakebase`

## Tools I work with

| Area | Tools |
| --- | --- |
| AI and agents | Agno, LangGraph, MindsDB, MCP, OpenAI, Anthropic, Gemini, vision models |
| Data | Python, SQL, BigQuery, Dataform, dlt, Databricks, Spark |
| Applications | TypeScript, React, Next.js, FastAPI, PostgreSQL, Supabase |
| Infrastructure | Docker, Dokploy, Redis, Cloudflare, self-hosted Convex, MinIO, Cloud Run |
| Delivery and observability | GitHub Actions, Grafana, LangSmith, Braintrust, Sentry |

I have a degree in Information Systems and a postgraduate qualification in Data Science & Big Data. I'm currently pursuing postgraduate studies in AI at Universidade Federal de Viçosa.

[Connect with me on LinkedIn](https://www.linkedin.com/in/gabrielsntr/)
