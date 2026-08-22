# Sybase (sybase)

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
