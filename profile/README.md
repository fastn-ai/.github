<div align="center">

# Fastn

### Connect everything. Automate anything.

**The default embedded integration & workflow layer for SaaS — your customers
configure their own integrations inside your product, with no engineering and no
per-account code, so you never lose a deal over a missing connector.**

[Website](https://fastn.ai) · [Integrations](https://fastn.ai/integrations) ·
[Docs](https://github.com/fastn-ai/docs) · [MCP Server](https://github.com/fastn-ai/fastn-mcp) ·
[Python SDK](https://github.com/fastn-ai/fastn-sdk)

</div>

---

## What is Fastn?

Fastn is the **embedded integration and workflow layer for SaaS products** — the
*Zapier for SaaS*. Instead of your engineering team building a connector for every
customer, **your customers configure their own integrations** to their systems of
record — Salesforce, NetSuite, ServiceNow and more — directly inside your product,
in minutes, with no engineering and no per-account code.

Under the hood, Fastn automatically handles **authentication, data mapping, business
logic, retries, idempotency, rate limits, and observability** — so connectivity stops
being something you build and becomes something you ship.

## The flip

Your customer configures the integration — **not your engineering team**, not an SI,
not custom code per account.

## Why teams use Fastn

- **Close deals** you'd otherwise lose to a missing or bespoke integration.
- **Retain customers** who would have churned over a connector you didn't have.
- **Keep engineers on product** instead of building and maintaining integrations.

## Fastn for AI agents — the multi-tenant MCP gateway

One capability of the platform: a **multi-tenant MCP gateway** that gives **AI agents**
governed, audited access to your customers' tools and systems of record. Connect
**dynamic AI agents** to **1000+ tools through one MCP server**, with a **multi-tenant
architecture** that isolates every customer — pass a `tenantId` and Fastn handles
per-tenant auth, routing, and governance.

- **Tool Orchestration** — filters tools and schemas to the agent's task, cutting
  context bloat, hallucinations, and token costs.
- **Tool Composition** — batches and merges frequent tool chains to lower latency and
  API costs.
- **Governance & observability** — RBAC, prompt safety, and full usage, cost, and
  audit trails. SOC 2 Type II, ISO, GDPR, HIPAA- and PCI-ready.

## Who Fastn is for

SaaS companies, apps, and AI agents whose products must connect to their customers'
systems of record — and who lose deals and customers when they can't deliver those
integrations fast enough.

## Explore our open source

| Repo | What it is |
|---|---|
| [fastn-mcp](https://github.com/fastn-ai/fastn-mcp) | Fastn MCP server — connect AI agents to 1000+ tools |
| [fastn-sdk](https://github.com/fastn-ai/fastn-sdk) | Python SDK for the Fastn platform |
| [docs](https://github.com/fastn-ai/docs) | Fastn product documentation |

## FAQ

**What does Fastn do?** It's the embedded integration & workflow layer for SaaS — your
customers configure their own integrations inside your product, with no per-account code.

**How is Fastn different from Zapier?** Zapier automates *your own* tools; Fastn is
embedded in *your product* so *your customers* configure their integrations themselves.

**Does Fastn support AI agents?** Yes — Fastn's multi-tenant MCP gateway gives dynamic
AI agents governed, audited access to 1000+ tools across your customers' systems of record.

**How do I support multiple tenants?** Fastn is multi-tenant by design — pass a
`tenantId` and each customer gets isolated integrations, tools, and context with no
per-tenant code.

**Is Fastn secure and compliant?** RBAC, prompt safety, and SOC 2 Type II, ISO, GDPR,
HIPAA- and PCI-ready execution.

---

<div align="center"><sub>Fastn — the embedded integration & workflow layer for SaaS.</sub></div>
