# Sybase (sybase)

A collection of APIs and resources for Sybase database systems.

**APIs.json:** [https://www.sap.com/products/data-cloud/sybase-ase.html](https://www.sap.com/products/data-cloud/sybase-ase.html)

## Tags

- Database
- Enterprise
- SAP
- SQL

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-19

## APIs

### Sybase ASE REST API

REST API for Sybase Adaptive Server Enterprise administration and monitoring. Provides programmatic access to server configuration, database management, performance monitoring, user administration, and backup operations.

- **Human URL:** [https://help.sap.com/docs/SAP_ASE](https://help.sap.com/docs/SAP_ASE)
- **Base URL:** `https://{server}:{port}/ase/v1`

#### Tags

- Administration
- Backup
- Database Management
- Monitoring
- Performance

#### Properties

- [Documentation](https://help.sap.com/docs/SAP_ASE)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/sybase/refs/heads/main/openapi/sybase-ase-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://help.sap.com/docs/SAP_ASE/authentication)
- [Changelog](https://help.sap.com/docs/SAP_ASE/791c41982ee345a19c4ec4b774222c4f/5db753f3a9c24ddcabc2581a98b99585.html)
- [Postman Collection](collections/sybase-ase-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sybase-ase-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sybase IQ REST API

REST API for SAP IQ (formerly Sybase IQ) analytics database.

- **Human URL:** [https://help.sap.com/docs/SAP_IQ](https://help.sap.com/docs/SAP_IQ)
- **Base URL:** `https://api.sybase.example.com/iq/v1`

#### Tags

- Analytics
- Big Data
- Data Warehouse

#### Properties

- [Documentation](https://help.sap.com/docs/SAP_IQ/REST_API)
- [OpenAPI](https://api.sybase.example.com/iq/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sybase-ase-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sybase-ase-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Mobile Platform API

APIs for Sybase mobile application development and management.

- **Human URL:** [https://help.sap.com/docs/SAP_MOBILE_PLATFORM](https://help.sap.com/docs/SAP_MOBILE_PLATFORM)
- **Base URL:** `https://api.sybase.example.com/mobile/v1`

#### Tags

- Application Development
- Mobile
- Synchronization

#### Properties

- [Documentation](https://help.sap.com/docs/SAP_MOBILE_PLATFORM/API)
- [SDK](https://help.sap.com/docs/SAP_MOBILE_PLATFORM/SDK)
- [Postman Collection](collections/sybase-ase-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sybase-ase-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP SQL Anywhere HTTP Web Services

SAP SQL Anywhere includes a built-in HTTP web server that exposes database objects as OData and REST web services. Developers can create SERVICE objects that transform SQL query results into XML, HTML, and JSON formats, and database tables and views can be automatically exposed via an OData producer.

- **Human URL:** [https://help.sap.com/docs/SAP_SQL_Anywhere](https://help.sap.com/docs/SAP_SQL_Anywhere)
- **Base URL:** `https://{server}:{port}`

#### Tags

- Database
- Embedded Database
- OData
- Web Services

#### Properties

- [Documentation](https://help.sap.com/docs/SAP_SQL_Anywhere)
- [Reference](https://help.sap.com/docs/SAP_SQL_Anywhere/98ad9ec940e2465695685d98e308dff5/8e8c9049a1fe448a820c5f5bc72119e7.html)
- [Getting Started](https://dcx.sap.com/)
- [Postman Collection](collections/sybase-ase-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sybase-ase-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SDK for SAP ASE

The SDK for SAP Adaptive Server Enterprise is a set of libraries and utilities for developing client applications. It includes SAP Open Client for C-language applications, Embedded SQL precompilers for C and COBOL, the ASE ODBC driver, ASE ADO.NET Data Provider, and jConnect for JDBC.

- **Human URL:** [https://help.sap.com/docs/SAP_ASE_SDK](https://help.sap.com/docs/SAP_ASE_SDK)
- **Base URL:** `https://{server}:{port}`

#### Tags

- Client Libraries
- Database Connectivity
- JDBC
- ODBC
- SDK

#### Properties

- [Documentation](https://help.sap.com/docs/SAP_ASE_SDK)
- [Reference](https://help.sap.com/docs/SAP_ASE_SDK/882ef48c7e9c4d6e845d98f34378db40/b21b7c31bbf91014ae38f7f5cc782b0b.html)
- [Getting Started](https://help.sap.com/docs/SAP_ASE_SDK/e12c539de04b44a0bb17a545a148361c/0d968d9bcca6462f9414cf6010088af9.html)
- [Postman Collection](collections/sybase-ase-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sybase-ase-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Replication Server

SAP Replication Server provides real-time data replication between SAP ASE databases and heterogeneous data sources. It uses Replication Command Language (RCL) to manage replication definitions, publications, and subscriptions for table and stored procedure replication.

- **Human URL:** [https://help.sap.com/docs/SAP_REPLICATION_SERVER](https://help.sap.com/docs/SAP_REPLICATION_SERVER)
- **Base URL:** `https://{server}:{port}`

#### Tags

- Data Synchronization
- High Availability
- Replication

#### Properties

- [Documentation](https://help.sap.com/docs/SAP_REPLICATION_SERVER)
- [Reference](https://help.sap.com/doc/efc57020a2914d40af14c48e08bfd01f/16.0.4.3/en-US/Replication_Server_Reference_Manual_en.pdf)
- [Getting Started](https://help.sap.com/doc/1699d891ffc746babeaf700da051f89e/16.0.4.1/en-US/SAP_RS_Quick_Start_ASE_en.pdf)
- [Postman Collection](collections/sybase-ase-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sybase-ase-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP ASE Cockpit

SAP ASE Cockpit is a web-based administration and management console for SAP Adaptive Server Enterprise. It provides monitoring, configuration, and management capabilities for ASE servers through a browser-based interface, replacing the earlier Adobe Flash-based console starting with ASE 16.0 SP04.

- **Human URL:** [https://help.sap.com/docs/SAP_ASE/9623e59098a24dc6b9013ba5d709309e/13ec24bd751e1014bf789ad719f1de31.html](https://help.sap.com/docs/SAP_ASE/9623e59098a24dc6b9013ba5d709309e/13ec24bd751e1014bf789ad719f1de31.html)
- **Base URL:** `https://{server}:{port}`

#### Tags

- Administration
- Management Console
- Monitoring

#### Properties

- [Documentation](https://help.sap.com/docs/SAP_ASE/9623e59098a24dc6b9013ba5d709309e/13ec24bd751e1014bf789ad719f1de31.html)
- [Getting Started](https://blogs.sap.com/2018/02/18/first-steps-with-sap-ase-cockpit/)
- [Postman Collection](collections/sybase-ase-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sybase-ase-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/sybase-software)
- [Portal](https://support.sap.com/sybase)
- [Support](https://support.sap.com/en/product/database.html)
- [Community](https://pages.community.sap.com/topics/applications-on-ase)
- [Downloads](https://support.sap.com/swdc)
- [Blog](https://blogs.sap.com/tags/products-sybase/)
- [Website](https://www.sap.com/products/data-cloud/sybase-ase.html)
- [Documentation](https://help.sap.com/docs/SAP_ASE)
- [Getting Started](https://help.sap.com/docs/SAP_ASE/9623e59098a24dc6b9013ba5d709309e/13ec24bd751e1014bf789ad719f1de31.html)
- [Terms of Service](https://www.sap.com/about/legal/terms-of-use.html)
- [Privacy Policy](https://www.sap.com/about/legal/privacy.html)
- [Status Page](https://www.sap.com/about/trust-center/cloud-service-status.html)
- [Changelog](https://help.sap.com/docs/SAP_ASE/791c41982ee345a19c4ec4b774222c4f/5db753f3a9c24ddcabc2581a98b99585.html)
- [Login](https://accounts.sap.com)
- [Sign Up](https://www.sap.com/products/technology-platform/sybase-ase/trial.html)
- [GitHub Organization](https://github.com/sqlanywhere)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/sybase)
- [S D Ks](https://help.sap.com/docs/SAP_ASE_SDK)
- [Pricing](https://www.sap.com/products/data-cloud/sybase-ase.html)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
