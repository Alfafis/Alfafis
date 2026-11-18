# Hi, I'm Rafael 👋

**AI Engineer & Senior Full Stack Engineer** based in Belo Horizonte, Brazil · Founder of **RM Digital Solutions**

I put AI to work in production: **LLM agents**, tool calling, **RAG** and agent memory, **MCP**, code-enforced guardrails, and LLM evaluation and observability, on top of a solid full-stack base: **React / Next.js**, **NestJS**, **Python/FastAPI** and **Java/Spring Boot**, **PostgreSQL** and **AWS**.

10+ years in tech · AI Engineer at Cogna (Cognalabs) · previously at Itaú Unibanco, Grupo Boticário, Loft and Petz · building for clients in Brazil, the US and Italy.

## AI engineering

- **Agents in production:** agent engine on AWS Bedrock (Claude) with flows editable without deploys, tool calling via the Converse API, SSE streaming and anti-hallucination guardrails (field-by-field human review, closed taxonomy, token and latency telemetry)
- **Multi-agent systems:** a 3-agent team with separate roles (data collection, decision, ledger/memory), scheduled routines, structured memory queried before every decision and an automated weekly evaluation
- **LLM observability:** logs, metrics and response temperature of AI flows with Datadog (Cogna)
- **Agentic engineering:** multi-model orchestration routed by the cost of an error, custom skills, hooks and MCP servers, versioned project memory (context, ADRs, sessions) across ~30 projects

## What I'm good at

- **Multi-tenant SaaS:** tenant isolation in two layers (`tenant_id` + Postgres RLS), queues (BullMQ, SQS), audit trails, ADR-driven decisions
- **Generative AI in production:** agent engine on AWS Bedrock (Claude) with tool calling, SSE streaming, prompts editable without deploys and anti-hallucination guardrails with human review
- **Integrations:** WhatsApp Cloud API (signed webhooks, idempotency, retries), payments (Pix, boleto, cards), ERPs and telephony
- **Security & privacy:** LGPD flows, MFA/2FA, CSP, data-leak fixes
- **AI-assisted engineering:** multi-model orchestration, MCP servers and open-source plugins for Claude Code

## Selected work

| Project | What it is |
| --- | --- |
| [World Automation Store](https://www.worldautomationstore.com) | B2B e-commerce for an Italian client, built from scratch: 150K SKUs migrated off WooCommerce, Next.js 15 + NestJS + Drizzle/PostgreSQL, AWS via Terraform, Bedrock AI module that translated 33K product names in parallel batches |
| White-label multi-tenant CRM | NestJS 11, Postgres RLS, Redis/BullMQ, ERP/telephony/WhatsApp integrations; region move cut latency from 152 ms to 26 ms |
| Be Planned | Monte Carlo SaaS (10K iterations, P10/P90) for mine-closure cost provisioning, in production with a mining client |
| Zapflow | Multi-tenant WhatsApp SaaS: Meta Cloud API + Baileys, HMAC-signed webhooks, AES-256-GCM secrets, Mercado Pago billing |
| [CondeNexo](https://github.com/Alfafis/CondeNexo.Api) | Access-control SaaS for residential condos with hash-chain audit trail and LGPD flows |

## Open source

- [**critique**](https://github.com/Alfafis/critique): permanent critical mindset for Claude Code. Approved in Anthropic's community marketplace, 208 tests, CI on Linux/macOS/Windows
- [**cc-token-statusline**](https://github.com/Alfafis/cc-token-statusline): token, context and quota telemetry for Claude Code (Python stdlib only)
- [**claude-mods**](https://github.com/Alfafis/claude-mods): file tree, subagent crew, context meter and session recall for Claude Code
- [**investimentos-ai**](https://github.com/Alfafis/investimentos-ai): autonomous B3 stock-analysis agent (paper trading) with its own MCP server (23 tools) and headless Claude Code routines

## Stack

**Frontend:** React · Next.js · TypeScript · TanStack Query · Tailwind · Jest/RTL · Cypress<br>
**Backend:** NestJS · Node.js · Java/Spring Boot · Python · REST · BullMQ · SQS<br>
**Data:** PostgreSQL (RLS, multi-tenant) · Drizzle · Redis · Supabase<br>
**Infra:** AWS (ECS, EKS, Lambda, RDS, Bedrock) · Terraform · Docker · Kubernetes · Cloudflare<br>
**AI:** Bedrock (Claude) · OpenAI · tool calling · SSE · multi-agent systems · RAG & agent memory · guardrails · human-in-the-loop · LLM observability (Datadog) · agent evaluation · MCP · Claude Code

## Let's talk

Open to freelance projects, contracts and full-time roles.<br>
[Portfolio](https://alfafis.github.io) · [LinkedIn](https://www.linkedin.com/in/alfafisteles)
