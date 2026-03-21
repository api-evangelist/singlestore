# SingleStore (singlestore)
SingleStore is a distributed SQL database platform designed for real-time analytics and transactional workloads at scale. Their cloud-managed service, SingleStore Helios, provides a developer platform with REST APIs for managing workspaces, executing SQL over HTTP, and connecting MongoDB-compatible applications without code changes.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/singlestore/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Database, SQL, Cloud, Analytics, Distributed

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-03-21

## APIs

### SingleStore Management API
The SingleStore Management API is a REST interface for programmatically creating and managing workspace groups and workspaces within SingleStore Helios, the cloud-managed distributed SQL database service. It supports operations for provisioning, updating, suspending, resuming, and deleting workspaces, as well as managing private connections, Flow instances, invitations, teams, and cloud workload identity configurations. Authentication uses HTTP Bearer tokens generated from the Cloud Portal, and all requests must be made over HTTPS. An OpenAPI specification is provided alongside the API to facilitate client SDK generation in multiple languages.

**Human URL:** [https://docs.singlestore.com/cloud/reference/management-api/](https://docs.singlestore.com/cloud/reference/management-api/)


#### Tags:

 - Cloud, Database, Workspace Management, Infrastructure

#### Properties

- [Documentation](https://docs.singlestore.com/cloud/reference/management-api/)
- [Documentation](https://docs.singlestore.com/cloud/reference/management-api/reference/)
- [OpenAPI](openapi/singlestore-management-api-openapi.yml)

### SingleStore Data API
The SingleStore Data API enables developers to execute SQL statements against a SingleStore Helios database over standard HTTP connections without requiring a native database driver. It supports all SQL statements available through a direct database connection, returning results as JSON-encoded responses using standard HTTP methods and response codes. The API exposes endpoints for executing DDL and DML statements via /api/v2/exec and returning query result sets via /api/v2/query/rows. Authentication is handled using HTTP Basic or Bearer Authentication over HTTPS, and the API supports up to 192 parallel requests per aggregator, making it suitable for serverless architectures and custom application integrations.

**Human URL:** [https://docs.singlestore.com/cloud/reference/data-api/](https://docs.singlestore.com/cloud/reference/data-api/)


#### Tags:

 - Database, SQL, Query, Serverless

#### Properties

- [Documentation](https://docs.singlestore.com/cloud/reference/data-api/)
- [Documentation](https://docs.singlestore.com/cloud/reference/data-api/data-api-endpoint-reference/)
- [OpenAPI](openapi/singlestore-data-api-openapi.yml)
- [JSONSchema](json-schema/singlestore-query-schema.json)

### SingleStore Kai MongoDB API
SingleStore Kai is a MongoDB wire protocol-compatible API layer that allows existing MongoDB applications to connect to SingleStore Helios without code changes, data transformations, schema migrations, or query modifications. It implements the MongoDB 6.0 network protocol, making the service appear as a MongoDB server to client applications, and includes support for the BSON storage type introduced in SingleStore 8.5.1 for full compatibility with all MongoDB document field types. Kai enables developers to leverage SingleStore's distributed SQL engine for real-time analytics workloads that would otherwise be slow on MongoDB, with benchmark results showing 100x to 1000x faster analytical query performance. The API can be enabled per workspace from the SingleStore Cloud Portal.

**Human URL:** [https://docs.singlestore.com/cloud/reference/singlestore-kai/](https://docs.singlestore.com/cloud/reference/singlestore-kai/)


#### Tags:

 - Database, MongoDB, NoSQL, JSON, Compatibility

#### Properties

- [Documentation](https://docs.singlestore.com/cloud/reference/singlestore-kai/)
- [Documentation](https://docs.singlestore.com/cloud/reference/singlestore-kai/getting-started-with-singlestore-kai/)

## Common Properties

- [Portal](https://www.singlestore.com/cloud-trial/)
- [Documentation](https://docs.singlestore.com/)
- [Website](https://www.singlestore.com/)
- [PrivacyPolicy](https://www.singlestore.com/legal/privacy-policy/)
- [TermsOfService](https://www.singlestore.com/legal/terms-of-service/)
- [Support](https://support.singlestore.com/)
- [Blog](https://www.singlestore.com/blog/)
- [Login](https://portal.singlestore.com/)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
