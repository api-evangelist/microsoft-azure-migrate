# Azure Migrate (microsoft-azure-migrate)

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
