# Amazon WorkMail (amazon-workmail)

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
