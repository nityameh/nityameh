# Hi, I'm Nitya Mehta 👋

Software engineer in Bengaluru (B.Tech CSE, IIIT Jabalpur '26) with about a year of production experience on multi-tenant ticketing platforms for Japanese event clients (Django, PostgreSQL, Redis, AWS). I also build and ship AI products end to end: LangGraph agents, hybrid RAG on pgvector, and eval suites that gate prompt changes in CI.

**Open to SWE roles** (on-site, hybrid or remote).

## What I've built
- **Rate limiting at scale:** Redis rate limiting across 15 tiered rules for a high-traffic ticketing platform, plus a root-cause fix for a client-IP bug behind AWS ALB and nginx.
- **Event-driven pipelines:** EventBridge → Lambda → idempotent Django endpoints, sending email in 500-recipient batches with per-batch failure isolation.
- **Secure multi-tenant systems:** email 2FA, OTP password recovery, tenant isolation (IDOR) and race-condition fixes; deployed on AWS ECS Fargate and load-tested to 10,000 concurrent users.
- **AI engineering:** tool-calling agents with human approval, hybrid retrieval (pgvector + full-text search, fused with RRF), and CI-gated evals.
- **Competitive programming:** Meta Hacker Cup 2024 Round 2; 1600+ problems solved.

## Projects
- **Orga:** AI assistant on WhatsApp, Telegram and web for Indian freelancers. LangGraph agent, hybrid RAG with cited answers, Claude and Groq fallback chain, 32 evals in CI. Live with real users.
- **[n-stack](https://github.com/nityameh/n-stack):** Claude Code plugin that turns agent rules (no secrets, no skipped tests, read-only agents) into enforced hooks, plus a 15-skill dev lifecycle.
- **[IPL Batsman Stats](https://github.com/nityameh/ipl-batsman-stats):** analytics over 1,169 ball-by-ball IPL matches (2008–2025), with LLM-powered natural-language search validated through Zod.

## Tech
| | |
|---|---|
| **Languages** | Python, TypeScript, JavaScript, SQL, C++, Java |
| **Backend** | Django, Django REST Framework, Node.js, Express, FastAPI |
| **Frontend** | React, Next.js, Tailwind CSS |
| **Data** | PostgreSQL, pgvector, Redis, Prisma, SQLite |
| **AI** | LangGraph, RAG, LLM evals, Claude API, Groq, Gemini |
| **Cloud & DevOps** | AWS (ECS Fargate, Lambda, RDS, ElastiCache, ALB, EventBridge), Terraform, Docker, GitHub Actions |

## Contact
📫 [mehtanitya01@gmail.com](mailto:mehtanitya01@gmail.com) · [LinkedIn](https://www.linkedin.com/in/nitya-mehta-624027214/)
