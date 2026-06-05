# Barndoor (barndoor)

Barndoor AI is the control plane for agentic AI, providing secure access and governance for AI agents and Model Context Protocol (MCP) servers. Founded in 2024 by Oren Michels (founder of Mashery), Barndoor enables enterprise IT, security, and developer teams to register agents, govern MCP server access through policy, broker OAuth connections to backend SaaS, and proxy MCP traffic with runtime policy enforcement and full audit trails. The Barndoor Platform REST API manages servers, connections, policies, agents, and MCP / SSE request proxying. Python, TypeScript, and Go SDKs are published on GitHub alongside Rust SDKs (Cerbos, official MCP, MCP OAuth compliance suite) and a Crew AI example. Deployment options include SaaS (trial), private cloud, and on-premises (Enterprise).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/barndoor/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/barndoor/refs/heads/main/apis.yml)

## Tags

- AI Agents
- AI Governance
- Agentic AI
- MCP
- Model Context Protocol
- Policy Enforcement
- OAuth
- Identity
- Security
- Audit
- Control Plane

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Barndoor Platform API

REST API for the Barndoor Platform. Manage MCP server registrations, OAuth connections from agents to backend SaaS, access-control policies (with rules, restrictions, revisions, validation), AI agent registrations, and proxy live MCP requests (`/mcp/{server_name}`) and SSE streams (`/sse/{server_name}`) through Barndoor's policy enforcement and audit pipeline. JWT Bearer authentication via Auth0 OAuth 2.0 with PKCE; the SDK's `loginInteractive()` handles the OAuth flow.

- **Human URL:** [https://docs.barndoor.ai/api-reference/introduction](https://docs.barndoor.ai/api-reference/introduction)
- **Base URL:** `https://{organization_id}.platform.barndoor.ai`

#### Tags

- Platform API
- MCP
- Policy
- Agents
- Servers
- Connections
- Proxy

#### Properties

- [Documentation](https://docs.barndoor.ai/api-reference/introduction)
- [OpenAPI](openapi/barndoor-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/barndoor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/barndoor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://docs.barndoor.ai/api-reference/introduction)
- [SDK](https://docs.barndoor.ai/sdks/introduction)

### Barndoor Python SDK

Python SDK for the Barndoor AI Platform. Wraps the Platform REST API, handles Auth0 PKCE login (`loginInteractive()`), discovers governed MCP tools, brokers OAuth connections to backend SaaS, and exposes the catalog through Pythonic helpers compatible with OpenAI tool-calling and frameworks such as Crew AI.

- **Human URL:** [https://docs.barndoor.ai/sdks/python](https://docs.barndoor.ai/sdks/python)
- **Base URL:** `https://github.com/barndoor-ai/barndoor-python-sdk`

#### Tags

- Python SDK
- SDK
- MCP

#### Properties

- [Documentation](https://docs.barndoor.ai/sdks/python)
- [Repository](https://github.com/barndoor-ai/barndoor-python-sdk)
- [Postman Collection](collections/barndoor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/barndoor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Barndoor TypeScript SDK

TypeScript SDK for the Barndoor AI Platform. Browser- and Node-friendly client for Auth0 PKCE login, governed MCP tool discovery, OAuth connection initiation, and proxying MCP / SSE requests through Barndoor.

- **Human URL:** [https://docs.barndoor.ai/sdks/typescript](https://docs.barndoor.ai/sdks/typescript)
- **Base URL:** `https://github.com/barndoor-ai/barndoor-ts-sdk`

#### Tags

- TypeScript SDK
- SDK
- MCP

#### Properties

- [Documentation](https://docs.barndoor.ai/sdks/typescript)
- [Repository](https://github.com/barndoor-ai/barndoor-ts-sdk)
- [Postman Collection](collections/barndoor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/barndoor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Barndoor Go SDK

Go SDK for the Barndoor AI Platform. Server-side client for registering agents, managing MCP servers and policies, brokering OAuth connections, and proxying MCP requests from Go services.

- **Human URL:** [https://github.com/barndoor-ai/barndoor-go-sdk](https://github.com/barndoor-ai/barndoor-go-sdk)
- **Base URL:** `https://github.com/barndoor-ai/barndoor-go-sdk`

#### Tags

- Go SDK
- SDK
- MCP

#### Properties

- [Repository](https://github.com/barndoor-ai/barndoor-go-sdk)
- [Postman Collection](collections/barndoor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/barndoor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Official MCP Rust SDK

The official Rust SDK for the Model Context Protocol. Maintained under the Barndoor AI GitHub organization; provides primitives to build MCP clients and servers in Rust.

- **Human URL:** [https://github.com/barndoor-ai/official-mcp-rust-sdk](https://github.com/barndoor-ai/official-mcp-rust-sdk)
- **Base URL:** `https://github.com/barndoor-ai/official-mcp-rust-sdk`

#### Tags

- MCP
- Rust
- SDK

#### Properties

- [Repository](https://github.com/barndoor-ai/official-mcp-rust-sdk)
- [Postman Collection](collections/barndoor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/barndoor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cerbos Rust SDK

Rust SDK for Cerbos, the policy-decision-point used by Barndoor for attribute-based access control. Lets Rust services request policy decisions from a Cerbos PDP.

- **Human URL:** [https://github.com/barndoor-ai/cerbos-sdk-rust](https://github.com/barndoor-ai/cerbos-sdk-rust)
- **Base URL:** `https://github.com/barndoor-ai/cerbos-sdk-rust`

#### Tags

- Cerbos
- ABAC
- Policy
- Rust
- SDK

#### Properties

- [Repository](https://github.com/barndoor-ai/cerbos-sdk-rust)
- [Postman Collection](collections/barndoor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/barndoor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MCP OAuth Compliance Suite

Rust test suite that validates remote MCP servers against the MCP authorization specification - RFC 9728 (Protected Resource Metadata), RFC 8414 (Authorization Server Metadata), RFC 7591 (Dynamic Client Registration), and OAuth 2.1. Useful for vendors and customers verifying MCP server conformance before onboarding to Barndoor.

- **Human URL:** [https://github.com/barndoor-ai/mcp-auth-compliance](https://github.com/barndoor-ai/mcp-auth-compliance)
- **Base URL:** `https://github.com/barndoor-ai/mcp-auth-compliance`

#### Tags

- MCP
- OAuth
- Compliance
- Rust
- Conformance

#### Properties

- [Repository](https://github.com/barndoor-ai/mcp-auth-compliance)
- [Postman Collection](collections/barndoor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/barndoor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Barndoor + Crew AI Example

Reference Python demo application showing how to plug Barndoor-governed MCP tools into a Crew AI multi-agent workflow.

- **Human URL:** [https://github.com/barndoor-ai/barndoor-ai-crew-ai-python-example](https://github.com/barndoor-ai/barndoor-ai-crew-ai-python-example)
- **Base URL:** `https://github.com/barndoor-ai/barndoor-ai-crew-ai-python-example`

#### Tags

- Crew AI
- Python
- Example
- MCP

#### Properties

- [Repository](https://github.com/barndoor-ai/barndoor-ai-crew-ai-python-example)
- [Postman Collection](collections/barndoor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/barndoor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/barndoor-ai)
- [Website](https://barndoor.ai/)
- [Documentation](https://docs.barndoor.ai/)
- [API Reference](https://docs.barndoor.ai/api-reference/introduction)
- [OpenAPI](openapi/barndoor-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://docs.barndoor.ai/api-reference/introduction)
- [SDK](https://docs.barndoor.ai/sdks/introduction)
- [Portal](https://app.barndoor.ai/)
- [Sign Up](https://app.barndoor.ai/auth/signup/trial)
- [Tokens Management](https://app.barndoor.ai/settings/tokens)
- [Pricing](https://barndoor.ai/pricing)
- [Plans](plans/barndoor-plans-pricing.yml)
- [Rate Limits](rate-limits/barndoor-rate-limits.yml)
- [Fin Ops](finops/barndoor-finops.yml)
- [Git Hub](https://github.com/barndoor-ai)
- [Security](https://barndoor.ai/security/)
- [Trust Center](https://trust.barndoor.ai)
- [About](https://barndoor.ai/about-us/)
- [M C P Catalog](https://docs.barndoor.ai/mcp-servers/servers)
- [I P Allowlist](https://docs.barndoor.ai/how-tos/ip-whitelisting)
- [Log Export](https://docs.barndoor.ai/how-tos/log-export)
- [Spectral Rules](rules/barndoor-spectral-rules.yml)
- [Vocabulary](vocabulary/barndoor-vocabulary.yaml)
- [JSON-LD](json-ld/barndoor-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Features](undefined)
- [Use Cases](undefined)
- [Solutions](undefined)
- [Compliance](undefined)
- [L L Ms Txt](https://docs.barndoor.ai/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
