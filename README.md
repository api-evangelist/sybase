# Sybase

Sybase (now SAP Adaptive Server Enterprise) is a high-performance relational database management system designed for transaction-heavy enterprise applications. SAP ASE provides a REST API for server administration, database management, performance monitoring, user management, and backup operations.

- **Website:** https://www.sap.com/products/data-cloud/sybase-ase.html
- **Documentation:** https://help.sap.com/docs/SAP_ASE
- **Support Portal:** https://support.sap.com/sybase
- **Community:** https://pages.community.sap.com/topics/applications-on-ase

## APIs

### Sybase ASE REST API
REST API for SAP Adaptive Server Enterprise (ASE) administration and monitoring. Provides programmatic access to server configuration, database management, performance monitoring, user administration, and backup operations.

- **Documentation:** https://help.sap.com/docs/SAP_ASE
- **OpenAPI:** [openapi/sybase-ase-rest-api-openapi.yml](openapi/sybase-ase-rest-api-openapi.yml)

## Artifacts

| Type | Path |
|---|---|
| OpenAPI Specs | [openapi/](openapi/) |
| Spectral Rules | [rules/sybase-rules.yml](rules/sybase-rules.yml) |
| Naftiko Capabilities | [capabilities/](capabilities/) |
| JSON Schema | [json-schema/](json-schema/) |
| JSON Structure | [json-structure/](json-structure/) |
| JSON-LD Context | [json-ld/sybase-context.jsonld](json-ld/sybase-context.jsonld) |
| Examples | [examples/](examples/) |
| Vocabulary | [vocabulary/sybase-vocabulary.yml](vocabulary/sybase-vocabulary.yml) |

## Naftiko Capabilities

### Shared Definitions
- [capabilities/shared/sybase-ase-api.yaml](capabilities/shared/sybase-ase-api.yaml) — ASE REST API consumer

### Workflow Capabilities
- [capabilities/database-administration.yaml](capabilities/database-administration.yaml) — Database administration workflow (REST port 8080, MCP port 9090, 12 tools)

## Authentication

SAP ASE REST API supports HTTP Basic authentication and Bearer token authentication. Credentials correspond to SAP ASE server login accounts.

## Maintainers

- Kin Lane (kin@apievangelist.com)
