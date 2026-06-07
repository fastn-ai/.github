<div align="center">

# Fastn

**Say yes to the integrations you are losing customers over.**

</div>

Your product already covers the common integrations. Fastn covers the rest: the bespoke,
one-off connectors and workflows that pre-built catalogs cannot handle and that cost you up
to 30% of the customers you lose. It is the wildcard connector your customers configure
themselves, inside your product, so "we do not support that yet" turns into "yes."

Fastn is an embedded integration platform for SaaS products and AI agents.

<div align="center">

[Website](https://fastn.ai) · [Integrations](https://fastn.ai/integrations) ·
[Docs](https://github.com/fastn-ai/docs) · [MCP Server](https://github.com/fastn-ai/fastn-mcp) ·
[Python SDK](https://github.com/fastn-ai/fastn-sdk)

</div>

---

## Business outcomes

- **Win the deals you lose to "we don't support that."** Every bespoke integration request
  becomes a yes your customer configures, so your market stops being capped by your connector
  catalog.
- **Cut integration-driven churn.** Integrated customers churn ~58% less on average, and
  70-79% less in mid-market (Crossbeam, 2023).
- **Go live in days, not weeks.** Configured by the customer in days, versus weeks of
  engineering per connector.
- **Reclaim engineering capacity.** Connector build and maintenance time approaches zero.

## How Fastn compares

| Dimension | AI coding agents (e.g., Claude Code) | iPaaS (Merge, Paragon, Workato) | In-house | Fastn |
|---|---|---|---|---|
| Who does the work | Your engineers, AI-assisted | Your engineers build the flows | Your engineers | **Your customer, inside your product** |
| Bespoke custom objects & logic | Yes, but re-generated per customer | Breaks on custom and bespoke logic | Yes, one-off per customer | **Yes, customer-configured** |
| Production hardening (auth refresh, retries, rate limits, idempotency, observability) | AI writes the happy path; you engineer each concern per connector | Partial; per-customer logic still on you | You build all of it | **Built in at the platform level** |
| Multi-tenant runtime & isolation | You build it | Usually not your brand | You build it | **Native: per-tenant auth, data, permissions** |
| Maintenance when an API changes | You regenerate, review, redeploy | Your engineers fix it | Your engineers fix it | **Monitoring agent plus AI testing agents keep it working** |
| Embedded in your product | Whatever you wire around it | Their widget | Yes, you build the embed | **Yes, white-label** |
| AI-native (build and maintain) | Drafting only | No | No | **Yes, end to end** |
| Time to a customer's integration | Hours to draft, weeks to harden | Weeks of engineering | Weeks per customer | **Days, customer-driven** |
| Cost as you scale | Engineering time per connector | Expensive at scale | Hits the backlog wall | **Pay only for active customers** |

## How it works

Your customer authorizes their own Salesforce, NetSuite, or ServiceNow, including custom
objects, custom tables, and bespoke logic, and describes what the data and workflows should
do. Fastn configures authentication, data mapping, business logic, retries, idempotency,
rate limits, and observability automatically. The customer configures the integration, not
your engineering team.

## Built for CRM and ERP

CRM and ERP are where integrations get hardest, and where pre-built catalogs and generated
code break. Every customer's Salesforce or HubSpot has different custom objects and fields;
every NetSuite has its own multi-entity GL and custom records; every ServiceNow has bespoke
tables and event rules. Fastn supports the 70+ CRMs your product needs, plus the ERPs and
systems of record like NetSuite and ServiceNow, and handles that customization natively:
your customer maps their own objects, fields, and logic, and the platform keeps it running
as their setup changes, without a one-off build per customer.

Beyond CRM and ERP, Fastn connects across 1000+ tools, and products serving sales, marketing,
customer success, and support teams benefit immediately, because their customers expect them
to plug into whatever stack they already run.

## Maintenance and operations, handled

The integrations don't become your maintenance burden. The platform runs them:

- **Monitoring agent on every production integration:** continuous health, with issues
  surfaced before your customers notice.
- **AI that builds and maintains:** connector builder, workflow builder, and testing agents
  create and keep connectors working, including when upstream APIs change.
- **Unlimited connectors & workflows:** custom objects, custom tables, bespoke and custom
  connectors included.
- **Free sandboxes:** unlimited test environments; test traffic never bills.
- **White-label embed:** your brand; your customers never see Fastn.
- **Enterprise-ready:** SOC 2 Type II, 99.9% uptime SLA, multi-tenant governance and audit,
  named solutions engineer.

## Fastn for AI agents (the multi-tenant MCP gateway)

For products with AI agents, Fastn exposes the same integrations as a governed MCP gateway,
built multi-tenant from the ground up:

- **One MCP endpoint, every customer isolated.** Pass a tenant identifier and each customer's
  agents see only that customer's authorized tools, data, and systems, without writing
  separate code per customer.
- **Governed tool access.** Agents act inside customer systems within their permissions, with
  RBAC, audit trails, and data masking on every call.
- **Built on the same connectors.** Agents reach each customer's Salesforce, NetSuite,
  ServiceNow, and custom systems through the integrations already configured in your product.
- **One capability of the platform:** the agent surface on top of the integration platform,
  not a separate product.

## Who it's for

SaaS products and AI agents that connect to their customers' systems of record, and whose
bespoke integration requests are capping their market or driving churn.

## Open source

| Repo | What it is |
|---|---|
| [fastn-mcp](https://github.com/fastn-ai/fastn-mcp) | Fastn MCP server: connect AI agents to your tools |
| [fastn-sdk](https://github.com/fastn-ai/fastn-sdk) | Python SDK for the Fastn platform |
| [docs](https://github.com/fastn-ai/docs) | Fastn product documentation |

## FAQ

**What is Fastn?** An embedded integration platform for SaaS products and AI agents. It covers
the bespoke, one-off integrations and workflows your pre-built catalog cannot, configured by
the customer inside your product.

**Who maintains the integrations?** Fastn does. A monitoring agent watches every production
integration, and AI testing agents keep connectors working as upstream APIs change, with no
per-customer maintenance on your team.

**How fast can a customer integration go live?** Days, configured by the customer, versus
weeks of engineering per connector.

**How does the multi-tenant MCP gateway work?** One MCP endpoint serves all your customers;
each tenant is isolated, and an agent only accesses the tools and systems that customer
authorized, with full audit and data masking.

**How does Fastn affect churn?** Integrated customers churn ~58% less on average, and 70-79%
less in mid-market (Crossbeam, 2023).

**What can Fastn connect to?** Customer systems of record such as Salesforce, NetSuite, and
ServiceNow, including custom objects, custom tables, and bespoke logic, plus 1000+ tools
across the rest of your customers' stack.

---

<div align="center"><sub>Fastn: say yes to every integration your customers ask for.</sub></div>
