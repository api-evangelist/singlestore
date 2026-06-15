# SingleStore (singlestore)

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
