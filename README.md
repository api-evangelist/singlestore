# SingleStore (singlestore)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

SingleStore is a cloud-native distributed SQL database designed for real-time analytics and mixed workloads. It offers a management API for provisioning and managing cloud workspaces, and a data API for executing SQL statements over HTTP without requiring native database drivers. SingleStore Helios is the fully managed cloud service providing serverless database capabilities with elastic scaling.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/singlestore/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/singlestore/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Database
- SQL
- Analytics
- Cloud
- Distributed SQL

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### SingleStore Data API

The SingleStore Data API enables developers to execute SQL statements against a SingleStore Helios database over standard HTTP connections without requiring a native database driver or MySQL-compatible client. It supports all SQL statements via /api/v2/exec, and returns query result sets via /api/v2/query/rows and /api/v2/query/tuples. Authentication is handled using HTTP Basic or Bearer Authentication over HTTPS.

- **Human URL:** [https://docs.singlestore.com/cloud/reference/data-api/](https://docs.singlestore.com/cloud/reference/data-api/)
- **Base URL:** `https://{workspaceHost}`

#### Tags

- SQL
- Database
- Query
- HTTP SQL

#### Properties

- [Documentation](https://docs.singlestore.com/cloud/reference/data-api/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/singlestore/refs/heads/main/openapi/singlestore-data-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/singlestore-data-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/singlestore-data-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/singlestore-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/singlestore-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SingleStore Management API

The SingleStore Management API is a REST interface for programmatically creating and managing workspace groups and workspaces within SingleStore Helios. It supports provisioning, updating, suspending, resuming, and deleting workspaces, as well as managing private connections, regions, organizations, jobs, files, secrets, and teams.

- **Human URL:** [https://docs.singlestore.com/cloud/reference/management-api/](https://docs.singlestore.com/cloud/reference/management-api/)
- **Base URL:** `https://api.singlestore.com/v1`

#### Tags

- Management
- Workspaces
- Provisioning
- Database

#### Properties

- [Documentation](https://docs.singlestore.com/cloud/reference/management-api/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/singlestore/refs/heads/main/openapi/singlestore-management-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/singlestore-data-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/singlestore-data-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/singlestore-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/singlestore-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/singlestore)
- [Website](https://www.singlestore.com/)
- [Developer Portal](https://docs.singlestore.com/)
- [Documentation](https://docs.singlestore.com/cloud/)
- [Pricing](https://www.singlestore.com/pricing/)
- [Blog](https://www.singlestore.com/blog/)
- [Git Hub Org](https://github.com/singlestore-labs)
- [Sign Up](https://www.singlestore.com/cloud-trial/)
- [Terms of Service](https://www.singlestore.com/cloud-terms-and-conditions/)
- [Privacy Policy](https://www.singlestore.com/privacy-policy/)
- [Support](https://support.singlestore.com)
- [Integrations](https://www.singlestore.com/partners/)
- [L L Ms Txt](https://docs.singlestore.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
