# Amazon WorkMail (amazon-workmail)
Amazon WorkMail is a secure, managed business email and calendar service with support for existing desktop and mobile email client applications. It provides encrypted mailboxes, corporate calendaring, full Outlook compatibility, and enterprise-grade security controls for business communications. WorkMail integrates with Active Directory, supports IMAP and Exchange ActiveSync for mobile devices, and provides 80 API operations for programmatic management.

**URL:** [https://raw.githubusercontent.com/api-evangelist/amazon-workmail/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/amazon-workmail/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Business Communication, Calendar, Email, Exchange, Enterprise

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon WorkMail API
The Amazon WorkMail API provides programmatic access to manage organizations, users, groups, aliases, mailboxes, resources, and mobile device access. It enables automation of email infrastructure provisioning and management for enterprise deployments with 80 operations.

**Human URL:** [https://aws.amazon.com/workmail/](https://aws.amazon.com/workmail/)

#### Tags:

 - AWS, Calendar, Email, Enterprise

#### Properties

- [Documentation](https://docs.aws.amazon.com/workmail/latest/adminguide/)
- [APIReference](https://docs.aws.amazon.com/workmail/latest/APIReference/)
- [GettingStarted](https://docs.aws.amazon.com/workmail/latest/adminguide/getting_started.html)
- [Pricing](https://aws.amazon.com/workmail/pricing/)
- [FAQ](https://aws.amazon.com/workmail/faqs/)
- [OpenAPI](openapi/amazon-workmail-openapi-original.yaml)
- [JSONSchema](json-schema/workmail-organization-schema.json)
- [JSONLD](json-ld/amazon-workmail-context.jsonld)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [Website](https://aws.amazon.com/workmail/)
- [Documentation](https://docs.aws.amazon.com/workmail/latest/adminguide/)
- [Console](https://console.aws.amazon.com/workmail/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [SignUp](https://signin.aws.amazon.com/signup?request_type=register)
- [Login](https://aws.amazon.com/console/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [GitHubOrganization](https://github.com/aws)

## Features

| Name | Description |
|------|-------------|
| Outlook Compatibility | Native support for Microsoft Outlook on Windows and Mac OS X with free/busy scheduling, delegation, and out-of-office replies. |
| Enterprise-Grade Security | Automatic encryption at rest using AWS KMS and SSL encryption in transit with spam and virus protection. |
| Active Directory Integration | Integration with AWS Directory Service AD Connector and Microsoft Active Directory for seamless enterprise authentication. |
| Mobile Device Management | Exchange ActiveSync support with remote device encryption, lock, password reset, and wipe capabilities. |
| Exchange Interoperability | Hybrid environments with Microsoft Exchange Server 2010 and 2013 for gradual migration scenarios. |
| Administrative SDK | Programmatic API for managing users, groups, resources, and organizational settings at scale. |
| Email Flow Rules | Configurable rules for filtering and routing messages based on custom organizational policies. |
| Journaling and Archiving | Email journaling capabilities for compliance archiving and e-discovery requirements. |

## Use Cases

| Name | Description |
|------|-------------|
| Exchange Migration | Migrate from Microsoft Exchange to Amazon WorkMail with minimal disruption using hybrid environment support. |
| Enterprise Email Provisioning | Automate user and mailbox provisioning via API for large-scale enterprise deployments. |
| Compliance Email Archiving | Use journaling and encryption for HIPAA-compliant and regulatory email archiving programs. |
| Mobile Workforce Enablement | Provide secure mobile email access with ActiveSync and mobile device management policies. |
| Hybrid Cloud Email | Run WorkMail alongside existing Exchange infrastructure for gradual cloud migration. |

## Integrations

| Name | Description |
|------|-------------|
| AWS Directory Service | AD Connector and Simple AD for directory integration and single sign-on capabilities. |
| AWS KMS | Key Management Service for managing encryption keys for mailbox data at rest. |
| AWS CloudTrail | Audit logging of all WorkMail API calls for compliance and security monitoring. |
| AWS Lambda | Lambda integration for email flow rules and custom email processing workflows. |
| Microsoft Outlook | Native Outlook MAPI support for Windows and Mac desktops. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amazon WorkMail OpenAPI](openapi/amazon-workmail-openapi-original.yaml)

### JSON Schema

317 JSON Schema files extracted from the OpenAPI specification.

### JSON Structure

317 JSON Structure files converted from JSON Schema definitions.

### JSON-LD

- [Amazon WorkMail Context](json-ld/amazon-workmail-context.jsonld)

### Examples

146 example JSON files generated from JSON Schema definitions.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Amazon WorkMail API](capabilities/shared/workmail.yaml) — 5 operations for organization, user, group, and mobile device management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Email Management](capabilities/email-management.yaml) | Amazon WorkMail | 5 | IT Administrator, Email Operations |

## Vocabulary

- [Amazon WorkMail Vocabulary](vocabulary/amazon-workmail-vocabulary.yaml) — Unified taxonomy mapping 8 resources, 7 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amazon WorkMail Spectral Rules](rules/amazon-workmail-spectral-rules.yml) — 19 rules across 9 categories enforcing Amazon WorkMail API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
