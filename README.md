# Oracle Enterprise Manager (oracle-enterprise-manager)
Oracle Enterprise Manager (OEM) provides a comprehensive management platform for managing Oracle IT infrastructure and applications. The APIs enable programmatic access to monitoring, administration, and automation capabilities.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/oracle-enterprise-manager/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Cloud Management, Database Management, Enterprise Management, Infrastructure Management, Monitoring, Oracle

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-18

## APIs

### Oracle Enterprise Manager Cloud Control REST API
REST API for Oracle Enterprise Manager Cloud Control providing access to monitoring, configuration, and administration capabilities including targets, metrics, incidents, blackouts, credentials, user management, and deployment procedures.

**Human URL:** [https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/APIOverview.html](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/APIOverview.html)

#### Tags:

 - Administration, Cloud Control, Monitoring, REST API

#### Properties

- [Documentation](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/APIOverview.html)
- [OpenAPI](openapi/oracle-enterprise-manager-cloud-control-openapi.yml)
- [JSONSchema](json-schema/oracle-enterprise-manager-target-schema.json)
- [JSONLD](json-ld/oracle-enterprise-manager-context.jsonld)
- [Authentication](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/Authentication.html)
- [APIReference](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html)
- [GettingStarted](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/SendRequests.html)

### Enterprise Manager Command Line Interface (EM CLI)
Command-line interface providing scriptable access to Enterprise Manager functionality including target management, job operations, patching, provisioning, and administration tasks through verbs that can be used in shell scripts, Perl, and Python.

**Human URL:** [https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emcli/](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emcli/)

#### Tags:

 - Automation, CLI, Command Line, Scripting

#### Properties

- [Documentation](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emcli/)
- [GettingStarted](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emcli/getting-started-em-cli.html)
- [APIReference](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emcli/em-cli-verbs.html)
- [Authentication](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emcli/emcli-security.html)

## Common Properties

- [Portal](https://www.oracle.com/enterprise-manager/)
- [Documentation](https://docs.oracle.com/en/enterprise-manager/)
- [Support](https://www.oracle.com/support/)
- [Pricing](https://www.oracle.com/enterprise-manager/pricing.html)
- [Blog](https://blogs.oracle.com/oem/)
- [Training](https://education.oracle.com/enterprise-manager)
- [TermsOfService](https://www.oracle.com/legal/terms.html)
- [PrivacyPolicy](https://www.oracle.com/legal/privacy/)
- [GettingStarted](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/index.html)
- [ReleaseNotes](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrel/cloud-control-release-notes-emrel.html)
- [ChangeLog](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emcon/new-features-release-update.html)
- [Security](https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emsec/index.html)
- [Integrations](https://www.oracle.com/enterprise-manager/technologies/grafana/)
- [Resources](https://www.oracle.com/enterprise-manager/technologies/)

## Features

| Name | Description |
|------|-------------|
| Target Monitoring | Monitor Oracle databases, hosts, middleware, and custom applications with configurable metrics, thresholds, and alerting. |
| Incident Management | Correlate events into actionable incidents with severity, priority, escalation, and automated notification workflows. |
| Blackout Management | Schedule maintenance windows to suppress monitoring alerts during planned downtime without losing data collection. |
| Database Lifecycle Management | Automate database patching, upgrades, and fleet maintenance with Gold Images and compliance reporting. |
| Deployment Procedures | Create and manage multi-step deployment workflows for provisioning, patching, and configuration changes. |
| Cloud Self-Service | Enable Database as a Service with self-service provisioning, quota management, and request workflows. |

## Use Cases

| Name | Description |
|------|-------------|
| Infrastructure Monitoring | Centralized monitoring of Oracle databases, hosts, middleware, and applications with real-time metrics and alerting. |
| Automated Patching | Fleet-level database patching using Gold Images with compliance validation and rollback capabilities. |
| Incident Response | Detect, triage, and resolve infrastructure issues using correlated incidents with annotations and escalation. |
| Capacity Planning | Analyze metric trends over time to forecast resource needs and optimize infrastructure utilization. |

## Integrations

| Name | Description |
|------|-------------|
| Grafana | Visualize Enterprise Manager metrics in Grafana dashboards using the OEM data source plugin. |
| Oracle Cloud Infrastructure | Extend monitoring to OCI resources and hybrid cloud environments through unified management. |
| ServiceNow | Forward incidents to ServiceNow for ITSM integration and automated ticket creation. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Oracle Enterprise Manager Cloud Control REST API](openapi/oracle-enterprise-manager-cloud-control-openapi.yml)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Oracle Enterprise Manager Cloud Control REST API](capabilities/shared/cloud-control.yaml) — 12 operations for infrastructure monitoring and management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Infrastructure Management](capabilities/infrastructure-management.yaml) | Cloud Control | 15 | Infrastructure Administrator |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
