# SingleStore

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

SingleStore is a cloud-native distributed SQL database designed for real-time analytics and mixed workloads. It offers a management API for provisioning and managing cloud workspaces, and a data API for executing SQL statements over HTTP without requiring native database drivers. SingleStore Helios is the fully managed cloud service providing serverless database capabilities with elastic scaling.

**Areas:** Database · SQL · Analytics · Cloud · Distributed SQL

## SingleStore on APIs.io

Everything profiled for SingleStore is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/singlestore/](https://apis.io/providers/singlestore/)** — or go straight to one of the APIs or properties below.

### APIs (9)

- [SingleStore Files API](https://apis.io/apis/singlestore/singlestore-files-api/) — Upload, download, list, and delete files in the personal, shared, or models space within SingleStore Helios Spaces (stage storage).
- [SingleStore Health API](https://apis.io/apis/singlestore/singlestore-health-api/) — Health check operations for verifying connectivity to the Data API endpoint without requiring authentication credentials.
- [SingleStore Jobs API](https://apis.io/apis/singlestore/singlestore-jobs-api/) — Create, retrieve, list, and delete scheduled notebook jobs within SingleStore Helios. Jobs enable automated execution of notebooks on configurable schedules.
- [SingleStore Organizations API](https://apis.io/apis/singlestore/singlestore-organizations-api/) — Retrieve information about the current user's organization within SingleStore Helios.
- [SingleStore Queries API](https://apis.io/apis/singlestore/singlestore-queries-api/) — Execute SQL statements against a SingleStore Helios workspace over HTTP. Supports DDL, DML, and SELECT statements returning results as JSON.
- [SingleStore Regions API](https://apis.io/apis/singlestore/singlestore-regions-api/) — List available cloud provider regions that support workspace group creation, including shared tier regions.
- [SingleStore Secrets API](https://apis.io/apis/singlestore/singlestore-secrets-api/) — Manage organization-level secrets that can be referenced securely in notebooks and jobs without exposing plaintext credentials.
- [SingleStore Workspaces API](https://apis.io/apis/singlestore/singlestore-workspaces-api/) — Create, list, retrieve, update, suspend, resume, and delete workspaces within a workspace group. Workspaces are the compute resources that connect to a…
- [SingleStore Workspace Groups API](https://apis.io/apis/singlestore/singlestore-workspace-groups-api/) — Create, list, retrieve, update, and delete workspace groups within a SingleStore Helios organization. Workspace groups are logical containers that group…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Singlestore Agentic Access](https://apis.io/agentic-access/singlestore/singlestore-agentic-access/)

#### JSON Schema (20)

The data models the API reads and writes.

- [ExecRequest](https://apis.io/schemas/singlestore/singlestore-exec-request/)
- [ExecResponse](https://apis.io/schemas/singlestore/singlestore-exec-response/)
- [Job](https://apis.io/schemas/singlestore/singlestore-job/)
- [JobCreate](https://apis.io/schemas/singlestore/singlestore-job-create/)
- [JobExecution](https://apis.io/schemas/singlestore/singlestore-job-execution/)
- [Organization](https://apis.io/schemas/singlestore/singlestore-organization/)
- [SingleStore Data API Query](https://apis.io/schemas/singlestore/singlestore-query/)
- [QueryRequest](https://apis.io/schemas/singlestore/singlestore-query-request/)
- [QueryRowsResponse](https://apis.io/schemas/singlestore/singlestore-query-rows-response/)
- [QueryTuplesResponse](https://apis.io/schemas/singlestore/singlestore-query-tuples-response/)
- [Region](https://apis.io/schemas/singlestore/singlestore-region/)
- [Secret](https://apis.io/schemas/singlestore/singlestore-secret/)
- [SingleStore Workspace](https://apis.io/schemas/singlestore/singlestore-workspace/)
- [WorkspaceCreate](https://apis.io/schemas/singlestore/singlestore-workspace-create/)
- [WorkspaceDeleteResponse](https://apis.io/schemas/singlestore/singlestore-workspace-delete-response/)
- [WorkspaceGroup](https://apis.io/schemas/singlestore/singlestore-workspace-group/)
- [WorkspaceGroupCreate](https://apis.io/schemas/singlestore/singlestore-workspace-group-create/)
- [WorkspaceGroupDeleteResponse](https://apis.io/schemas/singlestore/singlestore-workspace-group-delete-response/)
- [WorkspaceGroupUpdate](https://apis.io/schemas/singlestore/singlestore-workspace-group-update/)
- [WorkspaceUpdate](https://apis.io/schemas/singlestore/singlestore-workspace-update/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Singlestore Workspace Structure](https://apis.io/json-structure/singlestore/singlestore-workspace-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Singlestore Context](https://apis.io/jsonld/singlestore/singlestore-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [SingleStore Vocabulary](https://apis.io/vocabularies/singlestore/singlestore-vocabulary/)

#### Examples (2)

Example requests and responses.

- [Singlestore Execute Sql Example](https://apis.io/examples/singlestore/singlestore-execute-sql-example/)
- [Singlestore Query Rows Example](https://apis.io/examples/singlestore/singlestore-query-rows-example/)

#### Collections (20)

Postman and Open Collection request collections.

- [SingleStore Data API](https://apis.io/collections/singlestore/open-singlestore-data-api/)
- [SingleStore Data Files API](https://apis.io/collections/singlestore/open-singlestore-files-api/)
- [SingleStore Data Files Health API](https://apis.io/collections/singlestore/open-singlestore-health-api/)
- [SingleStore Data Files Jobs API](https://apis.io/collections/singlestore/open-singlestore-jobs-api/)
- [SingleStore Management API](https://apis.io/collections/singlestore/open-singlestore-management-api/)
- [SingleStore Data Files Organizations API](https://apis.io/collections/singlestore/open-singlestore-organizations-api/)
- [SingleStore Data Files Queries API](https://apis.io/collections/singlestore/open-singlestore-queries-api/)
- [SingleStore Data Files Regions API](https://apis.io/collections/singlestore/open-singlestore-regions-api/)
- [SingleStore Data Files Secrets API](https://apis.io/collections/singlestore/open-singlestore-secrets-api/)
- [SingleStore Data Files WorkspaceGroups API](https://apis.io/collections/singlestore/open-singlestore-workspacegroups-api/)
- [SingleStore Data Files Workspaces API](https://apis.io/collections/singlestore/open-singlestore-workspaces-api/)
- [SingleStore Data Files API](https://apis.io/collections/singlestore/postman-singlestore-files-api/)
- [SingleStore Data Files Health API](https://apis.io/collections/singlestore/postman-singlestore-health-api/)
- [SingleStore Data Files Jobs API](https://apis.io/collections/singlestore/postman-singlestore-jobs-api/)
- [SingleStore Data Files Organizations API](https://apis.io/collections/singlestore/postman-singlestore-organizations-api/)
- [SingleStore Data Files Queries API](https://apis.io/collections/singlestore/postman-singlestore-queries-api/)
- [SingleStore Data Files Regions API](https://apis.io/collections/singlestore/postman-singlestore-regions-api/)
- [SingleStore Data Files Secrets API](https://apis.io/collections/singlestore/postman-singlestore-secrets-api/)
- [SingleStore Data Files WorkspaceGroups API](https://apis.io/collections/singlestore/postman-singlestore-workspacegroups-api/)
- [SingleStore Data Files Workspaces API](https://apis.io/collections/singlestore/postman-singlestore-workspaces-api/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Singlestore Files Api Overlay](https://apis.io/overlays/singlestore/singlestore-files-api-overlay/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [SingleStore — jsonschema rules](https://apis.io/rules/singlestore/singlestore-jsonschema-spectral-rules/)
- [SingleStore API Rules](https://apis.io/rules/singlestore/singlestore-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Singlestore Authentication](https://apis.io/security/singlestore/singlestore-authentication/)
- [Singlestore Domain Security](https://apis.io/security/singlestore/singlestore-domain-security/)
- [Singlestore Vulnerability Disclosure](https://apis.io/security/singlestore/singlestore-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Singlestore Plans Pricing](https://apis.io/plans/singlestore/singlestore-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Singlestore Rate Limits](https://apis.io/rate-limits/singlestore/singlestore-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Singlestore Finops](https://apis.io/finops/singlestore/singlestore-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.singlestore.com/)
- [Documentation](https://docs.singlestore.com/cloud/)
- [Pricing](https://www.singlestore.com/pricing/)
- [Support](https://support.singlestore.com)
- [Blog](https://www.singlestore.com/blog/)
- [Terms of service](https://www.singlestore.com/cloud-terms-and-conditions/)
- [Privacy policy](https://www.singlestore.com/privacy-policy/)

## API Evangelist rating

**Kin Score 45.7** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 58.8 |
| Contract governance | 28.0 |
| Operational transparency | 23.7 |
| Developer ergonomics | 39.3 |
| Access clarity | 42.1 |

**Agent readiness 26.8** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 26.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/singlestore/](https://apis.io/providers/singlestore/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for SingleStore: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/singlestore/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
