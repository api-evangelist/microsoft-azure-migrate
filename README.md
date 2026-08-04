# Azure Migrate (microsoft-azure-migrate)

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

Azure Migrate provides a unified platform for discovering, assessing, and migrating on-premises servers, infrastructure, applications, databases, and data to Azure. Its REST APIs enable programmatic management of migration projects, discovery, assessment, and replication workflows for VMs, databases, and web apps.

**APIs.json:** [https://azure.microsoft.com/en-us/services/azure-migrate/](https://azure.microsoft.com/en-us/services/azure-migrate/)

## Tags

- Assessment
- Cloud Migration
- Database Migration
- Discovery
- Migration
- Replication
- Server Migration

## Timestamps

- **Created:** 2026-03-13
- **Modified:** 2026-05-19

## APIs

### Azure Migrate Projects API

Create and manage Azure Migrate projects which serve as the central container for discovery, assessment, and migration activities. Projects group related assessment and migration solutions for a workload.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/migrate/projects](https://learn.microsoft.com/en-us/rest/api/migrate/projects)
- **Base URL:** `https://management.azure.com`

#### Tags

- Migrate Project
- Migration
- Project Management

#### Properties

- [OpenAPI](openapi/microsoft-azure-migrate-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-azure-migrate.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-migrate.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://learn.microsoft.com/en-us/rest/api/migrate/projects)
- [Authentication](https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow)
- [Getting Started](https://learn.microsoft.com/en-us/azure/migrate/create-manage-projects)

### Azure Migrate Assessments API

Create and manage assessments that evaluate on-premises servers and databases for Azure readiness, sizing, and cost. Returns Azure VM readiness, recommended SKUs, monthly cost estimates, and migration compatibility findings.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/migrate/assessment](https://learn.microsoft.com/en-us/rest/api/migrate/assessment)
- **Base URL:** `https://management.azure.com`

#### Tags

- Assessment
- Cost Estimation
- Readiness
- Sizing

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/migrate/assessment)
- [Reference](https://learn.microsoft.com/en-us/azure/migrate/concepts-assessment-calculation)
- [Getting Started](https://learn.microsoft.com/en-us/azure/migrate/tutorial-discover-vmware)
- [Postman Collection](collections/microsoft-azure-migrate.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-migrate.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Migrate Discovery API

Manage discovery sites and inventory of on-premises servers, databases, and applications. Provides agentless and agent-based discovery for VMware, Hyper-V, and physical servers as a basis for assessment and migration planning.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/migrate/discovery](https://learn.microsoft.com/en-us/rest/api/migrate/discovery)
- **Base URL:** `https://management.azure.com`

#### Tags

- Agentless
- Discovery
- Hyper-V
- Inventory
- VMware

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/migrate/discovery)
- [Reference](https://learn.microsoft.com/en-us/azure/migrate/migrate-appliance)
- [Postman Collection](collections/microsoft-azure-migrate.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-migrate.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Migrate Server Migration API

Replicate, test migrate, and migrate on-premises servers including VMware, Hyper-V, and physical machines to Azure. Manages replication jobs, fabrics, and protected items used for server migration.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/migrate/migration](https://learn.microsoft.com/en-us/rest/api/migrate/migration)
- **Base URL:** `https://management.azure.com`

#### Tags

- Cutover
- Replication
- Server Migration
- Test Migration

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/migrate/migration)
- [Getting Started](https://learn.microsoft.com/en-us/azure/migrate/tutorial-migrate-vmware)
- [Postman Collection](collections/microsoft-azure-migrate.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-migrate.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Database Migration Service API

Streamline the migration of on-premises databases to Azure data platforms with minimal downtime. Supports SQL Server, MySQL, PostgreSQL, MongoDB, and Oracle source databases moving to Azure SQL, Azure Database services, or Cosmos DB.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/datamigration](https://learn.microsoft.com/en-us/rest/api/datamigration)
- **Base URL:** `https://management.azure.com`

#### Tags

- Database Migration
- DMS
- MySQL
- PostgreSQL
- SQL Server

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/datamigration)
- [Reference](https://learn.microsoft.com/en-us/azure/dms/dms-overview)
- [Getting Started](https://learn.microsoft.com/en-us/azure/dms/quickstart-create-data-migration-service-portal)
- [Postman Collection](collections/microsoft-azure-migrate.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-migrate.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Migrate Web Apps Assessment API

Discover and assess on-premises ASP.NET and Java web apps running on IIS and Tomcat for migration to Azure App Service. Returns readiness findings, configuration issues, and recommended Azure App Service plans.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/migrate/concepts-azure-webapps-assessment-calculation](https://learn.microsoft.com/en-us/azure/migrate/concepts-azure-webapps-assessment-calculation)
- **Base URL:** `https://management.azure.com`

#### Tags

- App Service
- ASP.NET
- Java
- Web Apps

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/migrate/how-to-create-azure-app-service-assessment)
- [Reference](https://learn.microsoft.com/en-us/azure/migrate/concepts-azure-webapps-assessment-calculation)
- [Postman Collection](collections/microsoft-azure-migrate.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-migrate.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Migrate Data Box API

Order and manage Azure Data Box devices for offline data transfer of large datasets to Azure when network bandwidth is limited or unavailable. Supports Data Box, Data Box Disk, and Data Box Heavy offerings.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/databox](https://learn.microsoft.com/en-us/rest/api/databox)
- **Base URL:** `https://management.azure.com`

#### Tags

- Data Box
- Offline Transfer
- Storage Migration

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/databox)
- [Reference](https://learn.microsoft.com/en-us/azure/databox/data-box-overview)
- [Postman Collection](collections/microsoft-azure-migrate.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-migrate.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Site Recovery API

Replicate workloads running on physical and virtual machines from a primary site to a secondary location for disaster recovery and migration. Manages recovery vaults, replication policies, protected items, and recovery plans.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/recoveryservices](https://learn.microsoft.com/en-us/rest/api/recoveryservices)
- **Base URL:** `https://management.azure.com`

#### Tags

- ASR
- Disaster Recovery
- Recovery Vault
- Replication
- Site Recovery

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/recoveryservices)
- [Reference](https://learn.microsoft.com/en-us/azure/site-recovery/site-recovery-overview)
- [Postman Collection](collections/microsoft-azure-migrate.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-migrate.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://portal.azure.com)
- [Documentation](https://learn.microsoft.com/en-us/azure/migrate/)
- [Getting Started](https://learn.microsoft.com/en-us/azure/migrate/migrate-services-overview)
- [Authentication](https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow)
- [S D Ks](https://learn.microsoft.com/en-us/azure/developer/)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/azure-migrate/)
- [Status Page](https://status.azure.com/)
- [Support](https://azure.microsoft.com/en-us/support/options/)
- [Blog](https://azure.microsoft.com/en-us/blog/tag/azure-migrate/)
- [Changelog](https://learn.microsoft.com/en-us/azure/migrate/whats-new)
- [Terms of Service](https://azure.microsoft.com/en-us/support/legal/)
- [Privacy Policy](https://privacy.microsoft.com/en-us/privacystatement)
- [GitHub Organization](https://github.com/Azure)
- [Website](https://azure.microsoft.com/en-us/products/azure-migrate)
- [Login](https://portal.azure.com)
- [Sign Up](https://azure.microsoft.com/en-us/free)
- [L L Ms Txt](https://portal.azure.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
