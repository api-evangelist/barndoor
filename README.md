# Barndoor AI (barndoor)

Barndoor AI is the control plane for agentic AI, providing secure access and governance for AI agents and Model Context Protocol (MCP) servers. Founded in 2024 by Oren Michels (founder of Mashery), Barndoor enables enterprise IT, security, and developer teams to register agents, govern MCP server access through policy, broker OAuth connections to backend SaaS, and proxy MCP traffic with runtime policy enforcement and full audit trails. The Barndoor Platform REST API manages servers, connections, policies, agents, and MCP / SSE request proxying. Python, TypeScript, and Go SDKs are published on GitHub alongside Rust SDKs (Cerbos, official MCP, MCP OAuth compliance suite) and a Crew AI example. Deployment options include SaaS (trial), private cloud, and on-premises (Enterprise).

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/barndoor/refs/heads/main/apis.yml)

## Tags

- AI Agents, AI Governance, Agentic AI, MCP, Model Context Protocol, Policy Enforcement, OAuth, Identity, Security, Audit, Control Plane

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-15

## APIs

| AID | Name | Description |
|---|---|---|
| barndoor:platform-api | [Barndoor Platform API](https://docs.barndoor.ai/api-reference/introduction) | REST API to manage MCP servers, OAuth connections, policies, agents, and proxy MCP / SSE requests. Auth0 JWT Bearer with PKCE. |
| barndoor:python-sdk | [Barndoor Python SDK](https://docs.barndoor.ai/sdks/python) | Python SDK wrapping the Platform API and handling PKCE login. |
| barndoor:typescript-sdk | [Barndoor TypeScript SDK](https://docs.barndoor.ai/sdks/typescript) | TypeScript SDK for browsers and Node. |
| barndoor:go-sdk | [Barndoor Go SDK](https://github.com/barndoor-ai/barndoor-go-sdk) | Server-side Go SDK. |
| barndoor:official-mcp-rust-sdk | [Official MCP Rust SDK](https://github.com/barndoor-ai/official-mcp-rust-sdk) | Official Rust SDK for the Model Context Protocol. |
| barndoor:cerbos-sdk-rust | [Cerbos Rust SDK](https://github.com/barndoor-ai/cerbos-sdk-rust) | Rust SDK for Cerbos policy decision points. |
| barndoor:mcp-auth-compliance | [MCP OAuth Compliance Suite](https://github.com/barndoor-ai/mcp-auth-compliance) | Rust test suite validating remote MCP servers against RFC 9728 / 8414 / 7591 and OAuth 2.1. |
| barndoor:crew-ai-example | [Barndoor + Crew AI Example](https://github.com/barndoor-ai/barndoor-ai-crew-ai-python-example) | Reference Python demo plugging Barndoor-governed MCP tools into Crew AI. |

## Common Properties

- [Barndoor AI Website](https://barndoor.ai/)
- [Developer Documentation](https://docs.barndoor.ai/)
- [API Reference](https://docs.barndoor.ai/api-reference/introduction)
- [OpenAPI Spec](openapi/barndoor-openapi.yml)
- [Authentication (Auth0 OAuth 2.0 with PKCE)](https://docs.barndoor.ai/api-reference/introduction)
- [Barndoor SDKs](https://docs.barndoor.ai/sdks/introduction)
- [Barndoor App / Portal](https://app.barndoor.ai/)
- [Free Trial Signup](https://app.barndoor.ai/auth/signup/trial)
- [Platform API Tokens](https://app.barndoor.ai/settings/tokens)
- [Pricing](https://barndoor.ai/pricing)
- [Plans (API Commons)](plans/barndoor-plans-pricing.yml)
- [Rate Limits (API Commons)](rate-limits/barndoor-rate-limits.yml)
- [FinOps (FOCUS 1.3)](finops/barndoor-finops.yml)
- [GitHub Org](https://github.com/barndoor-ai)
- [Security](https://barndoor.ai/security/)
- [Trust Center](https://trust.barndoor.ai)
- [MCP Catalog (60+ servers)](https://docs.barndoor.ai/mcp-servers/servers)
- [Static Egress IPs for MCP Servers](https://docs.barndoor.ai/how-tos/ip-whitelisting)
- [Audit Log Export to S3-Compatible Storage](https://docs.barndoor.ai/how-tos/log-export)
- [Spectral Ruleset](rules/barndoor-spectral-rules.yml)
- [Vocabulary](vocabulary/barndoor-vocabulary.yaml)
- [Naftiko Capability](capabilities/ai-governance.yaml)
- [JSON-LD Context](json-ld/barndoor-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| MCP Governance | Secure access control and policy enforcement for Model Context Protocol servers. |
| Runtime Policy Enforcement | Continuous governance applied at the moment AI agents act, not just at login. |
| Right-Sized Permissions | Precise, scoped access for agents - not broad human-level permissions. |
| Context Filtering | Dynamically surface only policy-compliant MCP tools, optimizing the context window. |
| AI Agent Registry | Register internal and external agents, group them, and track activity. |
| OAuth Connection Brokering | Initiate and manage OAuth 2.0 connections from agents to backend SaaS. |
| MCP / SSE Proxying | Streaming proxy that injects credentials and enforces policy on every MCP and SSE request. |
| Policy Authoring (RBAC/ABAC) | Create, clone, version, validate, and apply Cerbos-based RBAC and ABAC policies. |
| Audit Dashboards and Activity Logs | Complete audit trails for every AI action, applied policy, and outcome. |
| Audit Log Export | Stream audit events as gzipped JSON Lines to S3 / GCS / MinIO / SeaweedFS buckets. |
| Shadow AI Discovery | Centralized visibility into unauthorized AI apps and agents. |
| Identity Provider Integration | Connect to existing enterprise IdPs (Keycloak-based) for SSO and identity. |
| Static Egress IPs | Five dedicated outbound IPs for whitelisting Barndoor traffic at MCP servers. |
| Private and On-Prem Deployment | SaaS, private cloud, and on-premises deployment options. |

## Use Cases

| Name | Description |
|------|-------------|
| Enterprise AI Governance | Apply access policies and governance to AI agents across the organization. |
| MCP Server Management | Centrally register, secure, and manage MCP server deployments. |
| Agentic Workflow Orchestration | Coordinate multi-agent workflows with security and accountability controls. |
| AI Security and Data Exfiltration Prevention | Prevent unauthorized AI agent actions and limit data exfiltration. |
| Shadow AI Discovery | Surface unauthorized AI apps and agents already running in the environment. |
| Developer Tooling for Governed Agents | Build agents safely with end-to-end policy enforcement via SDKs. |
| Microsoft 365 Agent Governance | Govern agents that work across Microsoft 365 (Excel, Outlook, Teams, OneDrive). |

## Solutions

| Solution | Description |
|----------|-------------|
| IT & Security Teams | Centralize AI governance, manage shadow AI, and enforce real-time access controls at scale. |
| Developers | Deploy agents safely without custom security logic, with end-to-end policy across dev, staging, and prod. |

## Compliance

| Certification | Details |
|---------------|---------|
| SOC 2 Type II | Barndoor holds a SOC 2 Type II attestation for security controls effectiveness over time. |

## Integrations

Salesforce, Notion, GitHub, GitLab, Slack, HubSpot, Microsoft 365, Microsoft Teams, Microsoft Excel, Microsoft Word, OneDrive, OneNote, PowerPoint, Outlook Mail, Outlook Calendar, Microsoft Planner, Microsoft Dynamics, SharePoint, Gmail, Google Calendar, Google Docs, Google Sheets, Google Slides, Google Drive, Atlassian, Linear, Asana, Monday, Basecamp, Aha!, Box, Dropbox, Figma, Airtable, Snowflake, Hex, Amplitude, SonarQube, Datadog, Grafana, Sentry, Harness, Finch, ServiceNow, Zendesk, Freshdesk, Intercom, Zoom, Fireflies.ai, Granola, Otter, Apollo, Attio, Close, Gong, Shopify, Zoho CRM, Stripe, Plaid, QuickBooks, Xero, Octagon, Crew AI, Auth0, Keycloak, Cerbos.

## Pricing (Public Tiers)

| Tier | Price | Non-Human Identities (Agents) | Support | Notes |
|------|-------|-------------------------------|---------|-------|
| Trial | $0 | Unlimited | Email | Self-serve free trial via app.barndoor.ai/auth/signup/trial. |
| Team | $500 / month (billed annually) | 250 | Email | Production teams. |
| Pro | Custom (Contact Sales) | 1,000 | Chat + Email | Adds Platform API access, log streaming, custom MCP servers. |
| Enterprise | Custom (Contact Sales) | Custom | 24x7 Dedicated | Adds private cloud / on-premises deployment. |

## Generated Artifacts

| Type | Count | Location |
|------|-------|----------|
| OpenAPI Spec | 1 | `openapi/barndoor-openapi.yml` |
| Operation Examples | 26 | `examples/barndoor-{operation}-example.json` |
| Schema Examples | 23 | `examples/barndoor-{schema}-example.json` |
| JSON Schemas | 24 | `json-schema/` |
| JSON Structures | 24 | `json-structure/` |
| JSON-LD Context | 1 | `json-ld/barndoor-context.jsonld` |
| Naftiko Capability | 1 | `capabilities/ai-governance.yaml` |
| Spectral Ruleset | 1 | `rules/barndoor-spectral-rules.yml` |
| Vocabulary | 1 | `vocabulary/barndoor-vocabulary.yaml` |
| Plans (API Commons) | 1 | `plans/barndoor-plans-pricing.yml` |
| Rate Limits (API Commons) | 1 | `rate-limits/barndoor-rate-limits.yml` |
| FinOps (FOCUS 1.3) | 1 | `finops/barndoor-finops.yml` |

## API Surface (Barndoor Platform API)

The Barndoor Platform API spans 19 paths and 26 operations across these tags:

- **Agents** - register, list, get, unregister AI agents; counts by type.
- **Servers** - create, list, get, update, delete MCP server registrations.
- **Connections** - initiate, get status, delete OAuth connections to MCP servers.
- **Policies** - list, get, create, update, clone, validate; list revisions; enable / disable restrictions; aggregate summary and filter definitions.
- **MCP Proxy** - stream MCP requests (`/mcp/{server}`) and SSE streams (`/sse/{server}`) to backend MCP servers with runtime policy enforcement.

Authentication: JWT Bearer via Auth0 OAuth 2.0 with PKCE; the Barndoor SDK's `loginInteractive()` handles the flow. Platform API keys can also be generated at https://app.barndoor.ai/settings/tokens.

Base URL pattern: `https://{organization_id}.platform.barndoor.ai` (Trial / Production) or `https://{organization_id}.mcp.barndoor.ai` (Enterprise).

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
