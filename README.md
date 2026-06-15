# Oracle Enterprise Manager (oracle-enterprise-manager)

Oracle Enterprise Manager (OEM) provides a comprehensive management platform for managing Oracle IT infrastructure and applications. The APIs enable programmatic access to monitoring, administration, and automation capabilities.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/oracle-enterprise-manager/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/oracle-enterprise-manager/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Cloud Management
- Database Management
- Enterprise Management
- Infrastructure Management
- Monitoring
- Oracle

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Oracle Enterprise Manager Cloud Control REST API

REST API for Oracle Enterprise Manager Cloud Control providing access to monitoring, configuration, and administration capabilities including targets, metrics, incidents, blackouts, credentials, user management, and deployment procedures.

- **Human URL:** [https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/APIOverview.html](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/APIOverview.html)
- **Base URL:** `https://<em-host>:<port>/em/api`

#### Tags

- Administration
- Cloud Control
- Monitoring
- REST API

#### Properties

- [Documentation](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/APIOverview.html)
- [OpenAPI](openapi/oracle-enterprise-manager-cloud-control-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/oracle-enterprise-manager-cloud-control.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-enterprise-manager-cloud-control.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/oracle-enterprise-manager-target-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/oracle-enterprise-manager-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Authentication](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/Authentication.html)
- [API Reference](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html)
- [Getting Started](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/SendRequests.html)

### Enterprise Manager Command Line Interface (EM CLI)

Command-line interface providing scriptable access to Enterprise Manager functionality including target management, job operations, patching, provisioning, and administration tasks through verbs that can be used in shell scripts, Perl, and Python.

- **Human URL:** [https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emcli/](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emcli/)
- **Base URL:** `https://<em-host>:<port>/em`

#### Tags

- Automation
- CLI
- Command Line
- Scripting

#### Properties

- [Documentation](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emcli/)
- [Getting Started](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emcli/getting-started-em-cli.html)
- [API Reference](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emcli/em-cli-verbs.html)
- [Authentication](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emcli/emcli-security.html)
- [Postman Collection](collections/oracle-enterprise-manager-cloud-control.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-enterprise-manager-cloud-control.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Enterprise Manager Job System API

API for creating, managing, and monitoring Enterprise Manager jobs and tasks including scheduling, execution tracking, and deployment procedures.

- **Human URL:** [https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html)
- **Base URL:** `https://<em-host>:<port>/em/websvcs/restful/emws/job`

#### Tags

- Automation
- Jobs
- Scheduling
- Task Management

#### Properties

- [Documentation](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/)
- [API Reference](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html)
- [Postman Collection](collections/oracle-enterprise-manager-cloud-control.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-enterprise-manager-cloud-control.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Enterprise Manager Metric and Monitoring API

API for accessing performance metrics, monitoring data, and alerting information including numeric metric data points over time, latest metric values, and metric group metadata.

- **Human URL:** [https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html)
- **Base URL:** `https://<em-host>:<port>/em/websvcs/restful/emws/metric`

#### Tags

- Alerts
- Metrics
- Monitoring
- Performance

#### Properties

- [Documentation](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/)
- [API Reference](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html)
- [Postman Collection](collections/oracle-enterprise-manager-cloud-control.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-enterprise-manager-cloud-control.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Enterprise Manager Target Management API

API for managing monitored targets including discovery, configuration, lifecycle operations, bulk property updates, and target type metadata.

- **Human URL:** [https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html)
- **Base URL:** `https://<em-host>:<port>/em/websvcs/restful/emws/target`

#### Tags

- Configuration
- Discovery
- Lifecycle
- Target Management

#### Properties

- [Documentation](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/)
- [API Reference](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html)
- [Postman Collection](collections/oracle-enterprise-manager-cloud-control.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-enterprise-manager-cloud-control.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Enterprise Manager Incidents and Events API

REST API for searching, viewing, and managing incidents and events in Enterprise Manager, including clearing, suppressing, unsuppressing incidents, viewing member events, and managing annotations.

- **Human URL:** [https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html)
- **Base URL:** `https://<em-host>:<port>/em/api/incidents`

#### Tags

- Alerting
- Events
- Incidents
- Troubleshooting

#### Properties

- [Documentation](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html)
- [API Reference](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html)
- [Postman Collection](collections/oracle-enterprise-manager-cloud-control.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-enterprise-manager-cloud-control.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Enterprise Manager Blackout Management API

REST API for managing blackouts (maintenance windows) in Enterprise Manager, including creating, editing, deleting, listing, and stopping blackouts, managing blackout reasons, and retrieving targets in blackouts.

- **Human URL:** [https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html)
- **Base URL:** `https://<em-host>:<port>/em/api/blackouts`

#### Tags

- Blackouts
- Maintenance Windows
- Scheduling

#### Properties

- [Documentation](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html)
- [API Reference](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html)
- [Postman Collection](collections/oracle-enterprise-manager-cloud-control.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-enterprise-manager-cloud-control.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Enterprise Manager Credentials Management API

REST API for managing named credentials, monitoring credentials, and preferred credentials in Enterprise Manager, including creating, listing, deleting, updating, testing, and searching credential types.

- **Human URL:** [https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html)
- **Base URL:** `https://<em-host>:<port>/em/api/credentials`

#### Tags

- Authentication
- Credentials
- Security

#### Properties

- [Documentation](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html)
- [API Reference](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html)
- [Security](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emsec/index.html)
- [Postman Collection](collections/oracle-enterprise-manager-cloud-control.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-enterprise-manager-cloud-control.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Enterprise Manager User Management API

REST API for managing Enterprise Manager users and roles, including creating, modifying, and deleting users and roles, managing privilege grants and role assignments, and listing secure resources and permissions.

- **Human URL:** [https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html)
- **Base URL:** `https://<em-host>:<port>/em/api/users`

#### Tags

- Permissions
- Roles
- Security
- User Management

#### Properties

- [Documentation](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html)
- [API Reference](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html)
- [Security](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emsec/index.html)
- [Postman Collection](collections/oracle-enterprise-manager-cloud-control.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-enterprise-manager-cloud-control.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Enterprise Manager Database Patching and Maintenance API

REST API for database maintenance operations including updates, upgrades, and patching, with support for creating and managing Gold Images, patch recommendations, compliance reporting, and Fleet Patching and Provisioning (FPP) integration.

- **Human URL:** [https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emlcm/patch-history.html](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emlcm/patch-history.html)
- **Base URL:** `https://<em-host>:<port>/em/api/dblm`

#### Tags

- Database Maintenance
- Fleet Maintenance
- Gold Images
- Lifecycle Management
- Patching

#### Properties

- [Documentation](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emlcm/patch-history.html)
- [API Reference](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html)
- [Postman Collection](collections/oracle-enterprise-manager-cloud-control.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-enterprise-manager-cloud-control.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Enterprise Manager Deployment Procedure API

REST API for managing deployment procedures including creating, submitting, and deleting procedures, managing procedure instances with resume, suspend, stop, and retry operations, and tracking execution history.

- **Human URL:** [https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html)
- **Base URL:** `https://<em-host>:<port>/em/api/deploymentProcedures`

#### Tags

- Automation
- Deployment
- Procedures
- Provisioning

#### Properties

- [Documentation](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html)
- [API Reference](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html)
- [Postman Collection](collections/oracle-enterprise-manager-cloud-control.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-enterprise-manager-cloud-control.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Enterprise Manager Database Backup Management API

REST API for configuring and managing database backup settings, fleet-level backup configuration, and scheduling backup operations in Enterprise Manager.

- **Human URL:** [https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html)
- **Base URL:** `https://<em-host>:<port>/em/api/databaseBackup`

#### Tags

- Backup Management
- Database Backup
- Recovery

#### Properties

- [Documentation](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html)
- [API Reference](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html)
- [Postman Collection](collections/oracle-enterprise-manager-cloud-control.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-enterprise-manager-cloud-control.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Enterprise Manager ZDLRA Management API

REST API for managing Oracle Zero Data Loss Recovery Appliance (ZDLRA) including adding and removing protected databases, creating and managing protection policies, creating archival backups, and retrieving restore information.

- **Human URL:** [https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html)
- **Base URL:** `https://<em-host>:<port>/em/api/zdlra`

#### Tags

- Data Protection
- Recovery Appliance
- ZDLRA
- Zero Data Loss

#### Properties

- [Documentation](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html)
- [API Reference](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html)
- [Postman Collection](collections/oracle-enterprise-manager-cloud-control.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-enterprise-manager-cloud-control.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Enterprise Manager SQL Execution REST API

REST API for executing SQL queries against database targets monitored by Enterprise Manager and against the Enterprise Manager repository, enabling custom data extraction for dashboards and KPI reports.

- **Human URL:** [https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emmon/executing-sql-rest-api.html](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emmon/executing-sql-rest-api.html)
- **Base URL:** `https://<em-host>:<port>/em/api/db/sql`

#### Tags

- Data Extraction
- Database Queries
- Reporting
- SQL Execution

#### Properties

- [Documentation](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emmon/executing-sql-rest-api.html)
- [API Reference](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html)
- [Postman Collection](collections/oracle-enterprise-manager-cloud-control.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-enterprise-manager-cloud-control.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Enterprise Manager Data Guard Administration REST API

REST API for managing Oracle Data Guard configurations in Enterprise Manager, enabling high availability operations including switchover, failover, and standby database management.

- **Human URL:** [https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emlcm/data-guard-administration-rest-api1.html](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emlcm/data-guard-administration-rest-api1.html)
- **Base URL:** `https://<em-host>:<port>/em/api/dataguard`

#### Tags

- Data Guard
- Disaster Recovery
- High Availability
- Standby Database

#### Properties

- [Documentation](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emlcm/data-guard-administration-rest-api1.html)
- [Postman Collection](collections/oracle-enterprise-manager-cloud-control.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-enterprise-manager-cloud-control.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Enterprise Manager Cloud APIs (DBaaS)

REST APIs for Database as a Service (DBaaS) operations enabling self-service database provisioning, request management, and quota administration through Enterprise Manager Cloud Control.

- **Human URL:** [https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.4/emclo/using-cloud-apis.html](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.4/emclo/using-cloud-apis.html)
- **Base URL:** `https://<em-host>:<port>/em/cloud`

#### Tags

- Cloud
- Database as a Service
- DBaaS
- Provisioning
- Self-Service

#### Properties

- [Documentation](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.4/emclo/using-cloud-apis.html)
- [API Reference](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.4/emclo/database-service-ssa-user-rest-apis.html)
- [Use Cases](https://docs.oracle.com/cd/E73210_01/EMCLO/GUID-99E7450E-4255-46B5-9C0E-DC520DE376D2.htm)
- [Postman Collection](collections/oracle-enterprise-manager-cloud-control.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-enterprise-manager-cloud-control.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Enterprise Manager Extensibility Development Kit (EDK) API

Extensibility Development Kit providing tools, utilities, and APIs for developing Enterprise Manager plug-ins to extend platform capabilities for custom target monitoring and management.

- **Human URL:** [https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/plug-ins.html](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/plug-ins.html)
- **Base URL:** `https://<em-host>:<port>/em`

#### Tags

- Custom Monitoring
- Extensibility
- Plugin Development
- SDK

#### Properties

- [Documentation](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/plug-ins.html)
- [Postman Collection](collections/oracle-enterprise-manager-cloud-control.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-enterprise-manager-cloud-control.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [GitHub Organization](https://github.com/oracle)
- [Portal](https://www.oracle.com/enterprise-manager/)
- [Documentation](https://docs.oracle.com/en/enterprise-manager/)
- [Support](https://www.oracle.com/support/)
- [Pricing](https://www.oracle.com/enterprise-manager/pricing.html)
- [Blog](https://blogs.oracle.com/oem/)
- [Training](https://education.oracle.com/enterprise-manager)
- [Terms of Service](https://www.oracle.com/legal/terms.html)
- [Privacy Policy](https://www.oracle.com/legal/privacy/)
- [Getting Started](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/index.html)
- [Release Notes](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrel/cloud-control-release-notes-emrel.html)
- [Changelog](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emcon/new-features-release-update.html)
- [Security](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emsec/index.html)
- [Integrations](https://www.oracle.com/enterprise-manager/technologies/grafana/)
- [Resources](https://www.oracle.com/enterprise-manager/technologies/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
