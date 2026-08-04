# Oracle Essbase (oracle-essbase)

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

Oracle Essbase is a multi-dimensional database management system that provides a multidimensional analytical platform for business intelligence applications, financial consolidation, planning, budgeting, and forecasting.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/oracle-essbase/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/oracle-essbase/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Analytics
- Budgeting
- Business Intelligence
- Financial Consolidation
- Multi-Dimensional Database
- OLAP
- Planning

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Oracle Essbase REST API

RESTful API for managing and interacting with Oracle Essbase applications, databases, and performing analytical operations. Enables automation of Essbase resource management with endpoints for applications, databases, calculations, data loads, and user management.

- **Human URL:** [https://docs.oracle.com/en/database/other-databases/essbase/21/essrt/index.html](https://docs.oracle.com/en/database/other-databases/essbase/21/essrt/index.html)
- **Base URL:** `https://{host}:{port}/essbase/rest/v1`

#### Tags

- Analytics
- Calculations
- Data Management
- OLAP
- REST API

#### Properties

- [Documentation](https://docs.oracle.com/en/database/other-databases/essbase/21/essrt/index.html)
- [OpenAPI](openapi/oracle-essbase-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/oracle-essbase-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-essbase-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://docs.oracle.com/en/database/other-databases/essbase/21/erest/op-rest-v1-sessions-post.html)
- [Reference](https://docs.oracle.com/en/database/other-databases/essbase/21/essrt/rest-endpoints.html)
- [Getting Started](https://docs.oracle.com/en/database/other-databases/essbase/21/essrt/api-essbase.html)
- [J S O N  Schema](json-schema/oracle-essbase-application-schema.json)
- [J S O N  Schema](json-schema/oracle-essbase-database-schema.json)
- [J S O N  Schema](json-schema/oracle-essbase-job-schema.json)
- [J S O N  Schema](json-schema/oracle-essbase-user-schema.json)
- [J S O N  Schema](json-schema/oracle-essbase-session-schema.json)
- [J S O N  Schema](json-schema/oracle-essbase-dimension-schema.json)
- [J S O N  Schema](json-schema/oracle-essbase-connection-schema.json)
- [J S O N  Schema](json-schema/oracle-essbase-script-schema.json)
- [J S O N  Schema](json-schema/oracle-essbase-filter-schema.json)
- [J S O N- L D  Context](json-ld/oracle-essbase-context.jsonld)

### Essbase Java API

Java API for developing applications that interact with Oracle Essbase for data loading, calculations, and retrievals. Provides libraries, samples, and documentation for building Essbase client tools in Java.

- **Human URL:** [https://docs.oracle.com/en/database/other-databases/essbase/21/esjav/](https://docs.oracle.com/en/database/other-databases/essbase/21/esjav/)

#### Tags

- Client Tools
- Data Loading
- Java
- Programming Interface
- SDK

#### Properties

- [Documentation](https://docs.oracle.com/en/database/other-databases/essbase/21/esjav/)
- [Postman Collection](collections/oracle-essbase-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-essbase-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Essbase C API

C API for building high-performance applications that interact with Essbase databases. Includes the Grid API for Smart View-like functionality and the Outline API for programmatic outline manipulation.

- **Human URL:** [https://docs.oracle.com/en/database/other-databases/essbase/21/esoac/](https://docs.oracle.com/en/database/other-databases/essbase/21/esoac/)

#### Tags

- C API
- Grid API
- Native Interface
- Outline API
- SDK

#### Properties

- [Documentation](https://docs.oracle.com/en/database/other-databases/essbase/21/esoac/)
- [Postman Collection](collections/oracle-essbase-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-essbase-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Essbase MaxL Scripting Interface

MaxL is the multi-dimensional database access language for Essbase that provides a scripting-based interface for administering and querying Essbase. It enables automation of administrative operations using statements rather than a series of commands.

- **Human URL:** [https://docs.oracle.com/en/database/other-databases/essbase/21/esssr/maxl.html](https://docs.oracle.com/en/database/other-databases/essbase/21/esssr/maxl.html)

#### Tags

- Administration
- Automation
- Database Management
- Query Language
- Scripting

#### Properties

- [Documentation](https://docs.oracle.com/en/database/other-databases/essbase/21/esssr/maxl.html)
- [Authentication](https://docs.oracle.com/en/database/other-databases/essbase/21/esssr/login-logout-cli-authentication.html)
- [Postman Collection](collections/oracle-essbase-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-essbase-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Essbase CLI (Command Line Interface)

Command-line interface for administering and managing Essbase applications and databases. Provides command-line access for common administrative tasks including application management, data operations, and server configuration.

- **Human URL:** [https://docs.oracle.com/en/database/other-databases/essbase/21/essug/](https://docs.oracle.com/en/database/other-databases/essbase/21/essug/)

#### Tags

- Administration
- Automation
- CLI
- Command Line
- Server Management

#### Properties

- [Documentation](https://docs.oracle.com/en/database/other-databases/essbase/21/essug/)
- [Postman Collection](collections/oracle-essbase-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-essbase-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://docs.oracle.com/en/database/other-databases/essbase/21/index.html)
- [Getting Started](https://docs.oracle.com/en/database/other-databases/essbase/21/essst/what-is-oracle-essbase.html)
- [Documentation](https://docs.oracle.com/en/database/other-databases/essbase/)
- [Authentication](https://docs.oracle.com/en/database/other-databases/essbase/21/essoa/weblogic-authentication.html)
- [Blog](https://blogs.oracle.com/proactivesupportepm/category/pse-essbase-on-premise)
- [Status Page](https://ocistatus.oraclecloud.com/)
- [Support](https://support.oracle.com)
- [Terms of Service](https://www.oracle.com/legal/terms/)
- [Privacy Policy](https://www.oracle.com/legal/privacy/privacy-policy/)
- [GitHub Organization](https://github.com/oracle-quickstart/oci-essbase)
- [Community](https://community.oracle.com/customerconnect/categories/oci-essbase)
- [Website](https://www.oracle.com/business-analytics/essbase.html)
- [Login](https://www.oracle.com/cloud/sign-in.html)
- [Sign Up](https://www.oracle.com/cloud/free/)
- [Downloads](https://www.oracle.com/database/technologies/essbase-downloads.html)
- [Tutorials](https://docs.oracle.com/en/database/other-databases/essbase/21/essug/essbase-tutorials.html)
- [Licensing](https://www.oracle.com/corporate/pricing/specialty-topics.html)
- [Changelog](https://docs.oracle.com/en/database/other-databases/essbase/21/essop/index.html)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
