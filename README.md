# Barndoor

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Barndoor AI is the control plane for agentic AI, providing secure access and governance for AI agents and Model Context Protocol (MCP) servers. Founded in 2024 by Oren Michels (founder of Mashery), Barndoor enables enterprise IT, security, and developer teams to register agents, govern MCP server access through policy, broker OAuth connections to backend SaaS, and proxy MCP traffic with runtime policy enforcement and full audit trails. The Barndoor Platform REST API manages servers, connections, policies, agents, and MCP / SSE request proxying. Python, TypeScript, and Go SDKs are published on GitHub alongside Rust SDKs (Cerbos, official MCP, MCP OAuth compliance suite) and a Crew AI example. Deployment options include SaaS (trial), private cloud, and on-premises (Enterprise).

**Areas:** AI Agents · AI Governance · MCP · Policy Enforcement · Authentication · Identity · Security · Audit · Control Plane

## Barndoor on APIs.io

Everything profiled for Barndoor is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/barndoor/](https://apis.io/providers/barndoor/)** — or go straight to one of the APIs or properties below.

### APIs (13)

- [Barndoor Python SDK](https://apis.io/apis/barndoor/python-sdk/) — Python SDK for the Barndoor AI Platform. Wraps the Platform REST API, handles Auth0 PKCE login (`loginInteractive()`), discovers governed MCP tools, brokers…
- [Barndoor TypeScript SDK](https://apis.io/apis/barndoor/typescript-sdk/) — TypeScript SDK for the Barndoor AI Platform. Browser- and Node-friendly client for Auth0 PKCE login, governed MCP tool discovery, OAuth connection…
- [Barndoor Go SDK](https://apis.io/apis/barndoor/go-sdk/) — Go SDK for the Barndoor AI Platform. Server-side client for registering agents, managing MCP servers and policies, brokering OAuth connections, and proxying…
- [Official MCP Rust SDK](https://apis.io/apis/barndoor/official-mcp-rust-sdk/) — The official Rust SDK for the Model Context Protocol. Maintained under the Barndoor AI GitHub organization; provides primitives to build MCP clients and…
- [Cerbos Rust SDK](https://apis.io/apis/barndoor/cerbos-sdk-rust/) — Rust SDK for Cerbos, the policy-decision-point used by Barndoor for attribute-based access control. Lets Rust services request policy decisions from a…
- [MCP OAuth Compliance Suite](https://apis.io/apis/barndoor/mcp-auth-compliance/) — Rust test suite that validates remote MCP servers against the MCP authorization specification - RFC 9728 (Protected Resource Metadata), RFC 8414…
- [Barndoor + Crew AI Example](https://apis.io/apis/barndoor/crew-ai-example/) — Reference Python demo application showing how to plug Barndoor-governed MCP tools into a Crew AI multi-agent workflow.
- [Barndoor Agents API](https://apis.io/apis/barndoor/barndoor-agents-api/) — Manage AI agent registrations
- [Barndoor Connections API](https://apis.io/apis/barndoor/barndoor-connections-api/) — Manage OAuth connections to MCP servers
- [Barndoor MCP Proxy API](https://apis.io/apis/barndoor/barndoor-mcp-proxy-api/) — Proxy requests to MCP servers
- [Barndoor Policies API](https://apis.io/apis/barndoor/barndoor-policies-api/) — Manage access control policies for agents and servers
- [Barndoor Policy API](https://apis.io/apis/barndoor/barndoor-policy-api/) — The Policy API from Barndoor — 1 operation(s) for policy.
- [Barndoor Servers API](https://apis.io/apis/barndoor/barndoor-servers-api/) — Manage MCP server instances

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [Moved to /providers/barndoor/](https://apis.io/servers/barndoor/barndoor/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Barndoor Agentic Access](https://apis.io/agentic-access/barndoor/barndoor-agentic-access/)

#### JSON Schema (24)

The data models the API reads and writes.

- [Agent](https://apis.io/schemas/barndoor/barndoor-agent/)
- [AgentCounts](https://apis.io/schemas/barndoor/barndoor-agent-counts/)
- [AgentDirectoryBase](https://apis.io/schemas/barndoor/barndoor-agent-directory-base/)
- [AgentPayload](https://apis.io/schemas/barndoor/barndoor-agent-payload/)
- [AgentResponse](https://apis.io/schemas/barndoor/barndoor-agent-response/)
- [ConnectionInitiationResponse](https://apis.io/schemas/barndoor/barndoor-connection-initiation-response/)
- [ConnectionStatusResponse](https://apis.io/schemas/barndoor/barndoor-connection-status-response/)
- [Error](https://apis.io/schemas/barndoor/barndoor-error/)
- [FilterCategory](https://apis.io/schemas/barndoor/barndoor-filter-category/)
- [FilterOption](https://apis.io/schemas/barndoor/barndoor-filter-option/)
- [PaginationMeta](https://apis.io/schemas/barndoor/barndoor-pagination-meta/)
- [PolicyDetail](https://apis.io/schemas/barndoor/barndoor-policy-detail/)
- [PolicyRevisionSummary](https://apis.io/schemas/barndoor/barndoor-policy-revision-summary/)
- [PolicyRule](https://apis.io/schemas/barndoor/barndoor-policy-rule/)
- [PolicyRuleCondition](https://apis.io/schemas/barndoor/barndoor-policy-rule-condition/)
- [PolicySummary](https://apis.io/schemas/barndoor/barndoor-policy-summary/)
- [ServerCreateRequest](https://apis.io/schemas/barndoor/barndoor-server-create-request/)
- [ServerCreateResponse](https://apis.io/schemas/barndoor/barndoor-server-create-response/)
- [ServerDetail](https://apis.io/schemas/barndoor/barndoor-server-detail/)
- [ServerSummary](https://apis.io/schemas/barndoor/barndoor-server-summary/)
- [ServerUpdateRequest](https://apis.io/schemas/barndoor/barndoor-server-update-request/)
- [UpdatePolicy](https://apis.io/schemas/barndoor/barndoor-update-policy/)
- [ValidatePolicyRequest](https://apis.io/schemas/barndoor/barndoor-validate-policy-request/)
- [ValidatePolicyResponse](https://apis.io/schemas/barndoor/barndoor-validate-policy-response/)

#### JSON Structure (24)

Data models expressed in JSON Structure.

- [Barndoor Agent Counts Structure](https://apis.io/json-structure/barndoor/barndoor-agent-counts-structure/)
- [Barndoor Agent Directory Base Structure](https://apis.io/json-structure/barndoor/barndoor-agent-directory-base-structure/)
- [Barndoor Agent Payload Structure](https://apis.io/json-structure/barndoor/barndoor-agent-payload-structure/)
- [Barndoor Agent Response Structure](https://apis.io/json-structure/barndoor/barndoor-agent-response-structure/)
- [Barndoor Agent Structure](https://apis.io/json-structure/barndoor/barndoor-agent-structure/)
- [Barndoor Connection Initiation Response Structure](https://apis.io/json-structure/barndoor/barndoor-connection-initiation-response-structure/)
- [Barndoor Connection Status Response Structure](https://apis.io/json-structure/barndoor/barndoor-connection-status-response-structure/)
- [Barndoor Error Structure](https://apis.io/json-structure/barndoor/barndoor-error-structure/)
- [Barndoor Filter Category Structure](https://apis.io/json-structure/barndoor/barndoor-filter-category-structure/)
- [Barndoor Filter Option Structure](https://apis.io/json-structure/barndoor/barndoor-filter-option-structure/)
- [Barndoor Pagination Meta Structure](https://apis.io/json-structure/barndoor/barndoor-pagination-meta-structure/)
- [Barndoor Policy Detail Structure](https://apis.io/json-structure/barndoor/barndoor-policy-detail-structure/)
- [Barndoor Policy Revision Summary Structure](https://apis.io/json-structure/barndoor/barndoor-policy-revision-summary-structure/)
- [Barndoor Policy Rule Condition Structure](https://apis.io/json-structure/barndoor/barndoor-policy-rule-condition-structure/)
- [Barndoor Policy Rule Structure](https://apis.io/json-structure/barndoor/barndoor-policy-rule-structure/)
- [Barndoor Policy Summary Structure](https://apis.io/json-structure/barndoor/barndoor-policy-summary-structure/)
- [Barndoor Server Create Request Structure](https://apis.io/json-structure/barndoor/barndoor-server-create-request-structure/)
- [Barndoor Server Create Response Structure](https://apis.io/json-structure/barndoor/barndoor-server-create-response-structure/)
- [Barndoor Server Detail Structure](https://apis.io/json-structure/barndoor/barndoor-server-detail-structure/)
- [Barndoor Server Summary Structure](https://apis.io/json-structure/barndoor/barndoor-server-summary-structure/)
- [Barndoor Server Update Request Structure](https://apis.io/json-structure/barndoor/barndoor-server-update-request-structure/)
- [Barndoor Update Policy Structure](https://apis.io/json-structure/barndoor/barndoor-update-policy-structure/)
- [Barndoor Validate Policy Request Structure](https://apis.io/json-structure/barndoor/barndoor-validate-policy-request-structure/)
- [Barndoor Validate Policy Response Structure](https://apis.io/json-structure/barndoor/barndoor-validate-policy-response-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Barndoor Context](https://apis.io/jsonld/barndoor/barndoor-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [barndoor API Vocabulary](https://apis.io/vocabularies/barndoor/barndoor-vocabulary/)

#### Examples (48)

Example requests and responses.

- [Barndoor Agent Counts Example](https://apis.io/examples/barndoor/barndoor-agent-counts-example/)
- [Barndoor Agent Directory Base Example](https://apis.io/examples/barndoor/barndoor-agent-directory-base-example/)
- [Barndoor Agent Example](https://apis.io/examples/barndoor/barndoor-agent-example/)
- [Barndoor Agent Payload Example](https://apis.io/examples/barndoor/barndoor-agent-payload-example/)
- [Barndoor Agent Response Example](https://apis.io/examples/barndoor/barndoor-agent-response-example/)
- [Barndoor Clone Policy Example](https://apis.io/examples/barndoor/barndoor-clone-policy-example/)
- [Barndoor Connection Initiation Response Example](https://apis.io/examples/barndoor/barndoor-connection-initiation-response-example/)
- [Barndoor Connection Status Response Example](https://apis.io/examples/barndoor/barndoor-connection-status-response-example/)
- [Barndoor Create Server Example](https://apis.io/examples/barndoor/barndoor-create-server-example/)
- [Barndoor Delete Connection Example](https://apis.io/examples/barndoor/barndoor-delete-connection-example/)
- [Barndoor Delete Server Example](https://apis.io/examples/barndoor/barndoor-delete-server-example/)
- [Barndoor Disable Restriction Example](https://apis.io/examples/barndoor/barndoor-disable-restriction-example/)
- [Barndoor Enable Restriction Example](https://apis.io/examples/barndoor/barndoor-enable-restriction-example/)
- [Barndoor Error Example](https://apis.io/examples/barndoor/barndoor-error-example/)
- [Barndoor Filter Category Example](https://apis.io/examples/barndoor/barndoor-filter-category-example/)
- [Barndoor Filter Option Example](https://apis.io/examples/barndoor/barndoor-filter-option-example/)
- [Barndoor Get Agent Counts Example](https://apis.io/examples/barndoor/barndoor-get-agent-counts-example/)
- [Barndoor Get Agent Example](https://apis.io/examples/barndoor/barndoor-get-agent-example/)
- [Barndoor Get Connection Status Example](https://apis.io/examples/barndoor/barndoor-get-connection-status-example/)
- [Barndoor Get Filter Definitions Example](https://apis.io/examples/barndoor/barndoor-get-filter-definitions-example/)
- [Barndoor Get Policies Summary Example](https://apis.io/examples/barndoor/barndoor-get-policies-summary-example/)
- [Barndoor Get Policy Example](https://apis.io/examples/barndoor/barndoor-get-policy-example/)
- [Barndoor Get Server Example](https://apis.io/examples/barndoor/barndoor-get-server-example/)
- [Barndoor Initiate Connection Example](https://apis.io/examples/barndoor/barndoor-initiate-connection-example/)
- [Barndoor List Agents Example](https://apis.io/examples/barndoor/barndoor-list-agents-example/)
- …and 23 more published on APIs.io

#### Collections (13)

Postman and Open Collection request collections.

- [Barndoor Platform API](https://apis.io/collections/barndoor/open-barndoor/)
- [Barndoor Platform Agents API](https://apis.io/collections/barndoor/open-barndoor-agents-api/)
- [Barndoor Platform Agents Connections API](https://apis.io/collections/barndoor/open-barndoor-connections-api/)
- [Barndoor Platform Agents MCP Proxy API](https://apis.io/collections/barndoor/open-barndoor-mcp-proxy-api/)
- [Barndoor Platform Agents Policies API](https://apis.io/collections/barndoor/open-barndoor-policies-api/)
- [Barndoor Platform Agents Policy API](https://apis.io/collections/barndoor/open-barndoor-policy-api/)
- [Barndoor Platform Agents Servers API](https://apis.io/collections/barndoor/open-barndoor-servers-api/)
- [Barndoor Platform Agents API](https://apis.io/collections/barndoor/postman-barndoor-agents-api/)
- [Barndoor Platform Agents Connections API](https://apis.io/collections/barndoor/postman-barndoor-connections-api/)
- [Barndoor Platform Agents MCP Proxy API](https://apis.io/collections/barndoor/postman-barndoor-mcp-proxy-api/)
- [Barndoor Platform Agents Policies API](https://apis.io/collections/barndoor/postman-barndoor-policies-api/)
- [Barndoor Platform Agents Policy API](https://apis.io/collections/barndoor/postman-barndoor-policy-api/)
- [Barndoor Platform Agents Servers API](https://apis.io/collections/barndoor/postman-barndoor-servers-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Barndoor — jsonschema rules](https://apis.io/rules/barndoor/barndoor-jsonschema-spectral-rules/)
- [Barndoor API Rules](https://apis.io/rules/barndoor/barndoor-spectral-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Barndoor Authentication](https://apis.io/security/barndoor/barndoor-authentication/)
- [Barndoor Domain Security](https://apis.io/security/barndoor/barndoor-domain-security/)
- [Barndoor Vulnerability Disclosure](https://apis.io/security/barndoor/barndoor-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Barndoor Plans Pricing](https://apis.io/plans/barndoor/barndoor-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Barndoor Rate Limits](https://apis.io/rate-limits/barndoor/barndoor-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Barndoor Finops](https://apis.io/finops/barndoor/barndoor-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://barndoor.ai/)
- [Documentation](https://docs.barndoor.ai/)
- [API reference](https://docs.barndoor.ai/api-reference/introduction)
- [Pricing](https://barndoor.ai/pricing)
- [Blog](http://barndoor.ai/feed/)
- [Security](https://barndoor.ai/security/)
- [Trust centre](https://trust.barndoor.ai)

## API Evangelist rating

**Kin Score 54.7** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 59.6 |
| Contract governance | 27.3 |
| Operational transparency | 39.5 |
| Developer ergonomics | 48.8 |
| Access clarity | 47.4 |

**Agent readiness 36.6** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | distinct |

**Regulatory alignment 27.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/barndoor/](https://apis.io/providers/barndoor/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Barndoor: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/barndoor/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
