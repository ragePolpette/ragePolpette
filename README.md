# Gianmarco Bastianelli

Backend .NET developer and AI engineer. I build local-first tooling that lets LLM agents work with real systems (databases, Bitbucket, memory, code search) behind explicit policies, audit trails and human confirmation.

Website: [gianmarcobastianelli.dev](https://gianmarcobastianelli.dev)

## Model Context Protocol servers

| Project | What it does |
| --- | --- |
| [llm-sql-db-mcp](https://github.com/ragePolpette/llm-sql-db-mcp) | Policy-driven SQL Server access for agents: per-target read/write policies, SQL guard rails, optional field-aware anonymization. |
| [llm-bitbucket-mcp](https://github.com/ragePolpette/llm-bitbucket-mcp) | Bitbucket Cloud pull requests and pipelines for agents, with a repository registry, per-repository merge gating and a two-step confirmed merge. |
| [llm-memory](https://github.com/ragePolpette/llm-memory) | Persistent, scoped memory for agent workflows with semantic retrieval, governance and an audit trail. |
| [llm_context](https://github.com/ragePolpette/llm_context) | Retrieval server for indexed code and technical documentation, backed by PostgreSQL and pgvector. |
| [mcp-dashboard](https://github.com/ragePolpette/mcp-dashboard) | Local control plane to run, monitor and configure the MCP stack, with logs, SQL targets and an encrypted secret vault. |

## Agent workflows and research

| Project | What it does |
| --- | --- |
| [Exodia](https://github.com/ragePolpette/Exodia) | Local-first harness that turns tickets into audited, policy-gated code changes with pluggable AI runtimes. |
| [Persona](https://github.com/ragePolpette/Persona) | Anonymize documents before sharing them with an AI, then restore the answer through a local encrypted vault. |
| [intra-model-memval-lab](https://github.com/ragePolpette/intra-model-memval-lab) | Auditable store and LoRA consolidation pipeline with promote/rollback for small language models. |
| [Jobbby](https://github.com/ragePolpette/Jobbby) | Collects job postings, scores them against a CV with an LLM and tracks application outcomes (.NET 8). |

## How I work

- Small, explicit tool surfaces instead of generic escape hatches.
- Production-grade fences by default: deny-by-default policies, secrets outside the repository, confirmation for irreversible actions.
- Tests with synthetic data, CI on every pull request, changes documented in English.
