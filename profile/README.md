<div align="center">

# Fastn

**The embedded integration and workflow layer for SaaS products and AI agents.**

</div>

Up to **30% of the customers you lose** leave over a one-off integration you don't
support — a custom connector or bespoke workflow that's too expensive to build per
account. Fastn is the **wildcard connector** that closes that gap: it augments your
marketplace so your product can support **any** customer's connector or workflow,
configured by the customer inside your product, with **no per-customer implementation
or maintenance** for your team.

<div align="center">

[Website](https://fastn.ai) · [Integrations](https://fastn.ai/integrations) ·
[Docs](https://github.com/fastn-ai/docs) · [MCP Server](https://github.com/fastn-ai/fastn-mcp) ·
[Python SDK](https://github.com/fastn-ai/fastn-sdk)

</div>

---

## Business outcomes

- **Win deals you're losing.** "Can you integrate with [their system]?" becomes "yes —
  configured inside our product." Your market stops being capped by what your engineers
  had time to build.
- **Cut integration-driven churn.** Integrated customers churn ~58% less on average, and
  70–79% less in mid-market (Crossbeam, 2023).
- **Go live in days, not weeks.** Customer-configured in days — versus weeks of
  engineering per connector.
- **Reclaim engineering capacity.** Connector build and maintenance time approaches zero.

## How Fastn compares

| Dimension | AI coding agents (e.g., Claude Code) | iPaaS (Merge, Paragon, Workato) | In-house | Fastn |
|---|---|---|---|---|
| Who does the work | Your engineers, AI-assisted | Your engineers build the flows | Your engineers | **Your customer, inside your product** |
| Bespoke custom objects & logic | Yes, but re-generated per customer | Breaks on custom and bespoke logic | Yes, one-off per customer | **Yes, customer-configured** |
| Production hardening (auth refresh, retries, rate limits, idempotency, observability) | AI writes the happy path; you engineer each concern per connector | Partial; per-customer logic still on you | You build all of it | **Built in at the platform level** |
| Multi-tenant runtime & isolation | You build it | Usually not your brand | You build it | **Native — per-tenant auth, data, permissions** |
| Maintenance when an API changes | You regenerate, review, redeploy | Your engineers fix it | Your engineers fix it | **Monitoring agent + AI testing agents keep it working** |
| Embedded in your product | Whatever you wire around it | Their widget | Yes, you build the embed | **Yes, white-label** |
| AI-native (build and maintain) | Drafting only | No | No | **Yes, end to end** |
| Time to a customer's integration | Hours to draft, weeks to harden | Weeks of engineering | Weeks per customer | **Days, customer-driven** |
| Cost as you scale | Engineering time per connector | Expensive at scale | Hits the backlog wall | **Pay only for active customers** |

## How it works

Your customer authorizes their own Salesforce, NetSuite, or ServiceNow — including custom
objects, custom tables, and bespoke logic — and describes what the data and workflows
should do. Fastn configures authentication, data mapping, business logic, retries,
idempotency, rate limits, and observability automatically.

## Built for CRM and ERP

CRM and ERP are where integrations get hardest — and where pre-built catalogs and
generated code break. Every customer's Salesforce or HubSpot has different custom objects
and fields; every NetSuite has its own multi-entity GL and custom records; every
ServiceNow has bespoke tables and event rules. Fastn supports the **70+ CRMs your product
needs** — plus the ERPs and systems of record like NetSuite and ServiceNow — and handles
that customization natively: your customer maps their own objects, fields, and logic, and
the platform keeps it running as their setup changes, with no bespoke build per account.

Beyond CRM and ERP, Fastn connects across 1000+ tools — and products serving sales,
marketing, customer success, and support teams benefit immediately, because their
customers expect them to plug into whatever stack they already run.

## Maintenance and operations, handled

The integrations don't become your maintenance burden — the platform runs them:

- **Monitoring agent on every production integration** — continuous health; issues
  surfaced before your customers notice.
- **AI that builds and maintains** — connector builder, workflow builder, and testing
  agents create and keep connectors working, including when upstream APIs change.
- **Unlimited connectors & workflows** — custom objects, custom tables, bespoke and custom
  connectors included.
- **Free sandboxes** — unlimited test environments; test traffic never bills.
- **White-label embed** — your brand; your customers never see Fastn.
- **Enterprise-ready** — SOC 2 Type II, 99.9% uptime SLA, multi-tenant governance and
  audit, named solutions engineer.

## Fastn for AI agents — the multi-tenant MCP gateway

For products with AI agents, Fastn exposes the same integrations as a governed MCP gateway,
built multi-tenant from the ground up:

- **One MCP endpoint, every customer isolated.** Pass a tenant identifier and each
  customer's agents see only that customer's authorized tools, data, and systems — no
  per-tenant code, no separate deployments.
- **Governed tool access.** Agents act inside customer systems within their permissions,
  with RBAC, audit trails, and data masking on every call.
- **Built on the same connectors.** Agents reach each customer's Salesforce, NetSuite,
  ServiceNow, and custom systems through the integrations already configured in your product.
- **One capability of the platform** — the agent surface on top of the embedded integration
  layer, not a separate product.

## Who it's for

SaaS products and AI agents that need to connect to their customers' systems of record, and
whose connector backlog is capping their market or driving churn.

## Open source

| Repo | What it is |
|---|---|
| [fastn-mcp](https://github.com/fastn-ai/fastn-mcp) | Fastn MCP server — connect AI agents to your tools |
| [fastn-sdk](https://github.com/fastn-ai/fastn-sdk) | Python SDK for the Fastn platform |
| [docs](https://github.com/fastn-ai/docs) | Fastn product documentation |

## FAQ

**What is Fastn?** The embedded integration and workflow layer for SaaS products and AI
agents — your customers configure their own integrations to their systems of record inside
your product, with no per-account code.

**Who maintains the integrations?** Fastn does. A monitoring agent watches every production
integration, and AI testing agents keep connectors working as upstream APIs change — no
per-customer maintenance on your team.

**How fast can a customer integration go live?** Days, configured by the customer — versus
weeks of engineering per connector.

**How does the multi-tenant MCP gateway work?** One MCP endpoint serves all your customers;
each tenant is isolated, and an agent only accesses the tools and systems that customer
authorized, with full audit and data masking.

**How does Fastn affect churn?** Integrated customers churn ~58% less on average, and 70–79%
less in mid-market (Crossbeam, 2023).

**What can Fastn connect to?** Customer systems of record such as Salesforce, NetSuite, and
ServiceNow — including custom objects, custom tables, and bespoke logic — plus 1000+ tools
across the rest of your customers' stack.

---

<div align="center"><sub>Fastn — the embedded integration and workflow layer for SaaS products and AI agents.</sub></div>
