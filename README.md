# SingleStore

SingleStore is a cloud-native distributed SQL database designed for real-time analytics and mixed workloads. It offers a management API for provisioning and managing cloud workspaces, and a data API for executing SQL statements over HTTP without requiring native database drivers. SingleStore Helios is the fully managed cloud service providing serverless database capabilities with elastic scaling.

**URL:** [https://raw.githubusercontent.com/api-evangelist/singlestore/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/singlestore/refs/heads/main/apis.yml)

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
- **Modified:** 2026-05-02

## APIs

### SingleStore Data API

The SingleStore Data API enables developers to execute SQL statements against a SingleStore Helios database over HTTP without requiring native database drivers.

**Human URL:** https://docs.singlestore.com/cloud/reference/data-api/
**Base URL:** https://{workspaceHost}

#### Properties

- [Documentation](https://docs.singlestore.com/cloud/reference/data-api/)
- [OpenAPI](openapi/singlestore-data-api-openapi.yml)

### SingleStore Management API

The SingleStore Management API provides programmatic control over workspace groups, workspaces, jobs, files, secrets, and organization settings.

**Human URL:** https://docs.singlestore.com/cloud/reference/management-api/
**Base URL:** https://api.singlestore.com/v1

#### Properties

- [Documentation](https://docs.singlestore.com/cloud/reference/management-api/)
- [OpenAPI](openapi/singlestore-management-api-openapi.yml)

## OpenAPI Specifications

- [Data API](openapi/singlestore-data-api-openapi.yml)
- [Management API](openapi/singlestore-management-api-openapi.yml)

## Capabilities

- [Database Operations](capabilities/database-operations.yaml) - Unified SQL execution and workspace management workflow

### Shared Definitions

- [Data API](capabilities/shared/data-api.yaml)
- [Management API](capabilities/shared/management-api.yaml)

## Rules

- [SingleStore Rules](rules/singlestore-rules.yml)

## JSON Schemas

- [Query Schema](json-schema/singlestore-query-schema.json)
- [Workspace Schema](json-schema/singlestore-workspace-schema.json)

## JSON Structures

- [Workspace Structure](json-structure/singlestore-workspace-structure.json)

## JSON-LD

- [SingleStore Context](json-ld/singlestore-context.jsonld)

## Examples

- [Execute SQL](examples/singlestore-execute-sql-example.json)
- [Query Rows](examples/singlestore-query-rows-example.json)

## Vocabulary

- [SingleStore Vocabulary](vocabulary/singlestore-vocabulary.yml)

## Common Links

- **Website:** https://www.singlestore.com/
- **Documentation:** https://docs.singlestore.com/
- **Pricing:** https://www.singlestore.com/pricing/
- **Blog:** https://www.singlestore.com/blog/
- **GitHub:** https://github.com/singlestore-labs
- **Sign Up:** https://www.singlestore.com/cloud-trial/
- **Support:** https://support.singlestore.com
- **Terms of Service:** https://www.singlestore.com/cloud-terms-and-conditions/
- **Privacy Policy:** https://www.singlestore.com/privacy-policy/

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
