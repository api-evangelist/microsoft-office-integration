# Microsoft Office Integration (microsoft-office-integration)

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

APIs for Microsoft Office Integration, connecting Microsoft Office components and systems for seamless data exchange and end-to-end workflows across multiple technologies and platforms. The Office 365 Management APIs provide a single extensibility platform for management tasks including service communications, security, compliance, reporting, and auditing, using common industry-standard approaches including OAuth v2, OData v4, and JSON.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/microsoft-office-integration/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/microsoft-office-integration/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Microsoft 365
- Microsoft Office Integration
- Office 365

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### Microsoft Office 365 Management Activity API

The Office 365 Management Activity API provides information about various user, admin, system, and policy actions and events from Office 365 and Microsoft Entra activity logs. It enables customers and partners to create or enhance operations, security, and compliance-monitoring solutions. The API supports subscription management, content retrieval, webhook notifications, and DLP sensitive type lookups across content types including Azure AD, Exchange, SharePoint, and General audit logs.

- **Human URL:** [https://learn.microsoft.com/en-us/office/office-365-management-api/office-365-management-activity-api-reference](https://learn.microsoft.com/en-us/office/office-365-management-api/office-365-management-activity-api-reference)

#### Tags

- Auditing
- Compliance
- Office 365
- Security

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/office/office-365-management-api/office-365-management-activity-api-reference)
- [OpenAPI](openapi/microsoft-office-management-activity-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-office-management-activity-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-office-management-activity-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/subscription.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/activity-record.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/content-blob.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/microsoft-office-integration-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Microsoft Office 365 Service Communications API

The Office 365 Service Communications API provides tenant administrators and partners with real-time service health information and Message Center communications. It enables access to the list of subscribed services, current and historical service status, incident details, and planned maintenance notifications for Office 365, Yammer, Dynamics CRM, and Microsoft Intune cloud services.

- **Human URL:** [https://learn.microsoft.com/en-us/office/office-365-management-api/office-365-service-communications-api-reference](https://learn.microsoft.com/en-us/office/office-365-management-api/office-365-service-communications-api-reference)

#### Tags

- Incidents
- Monitoring
- Office 365
- Service Health

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/office/office-365-management-api/office-365-service-communications-api-reference)
- [OpenAPI](openapi/microsoft-office-service-communications-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-office-service-communications-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-office-service-communications-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/service.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/workload-status.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/message.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/microsoft-office-integration-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Common Properties

- [GitHub Organization](https://github.com/OfficeDev)
- [Documentation](https://learn.microsoft.com/en-us/office/office-365-management-api/)
- [Documentation](https://learn.microsoft.com/en-us/graph/overview)
- [Getting Started](https://learn.microsoft.com/en-us/office/office-365-management-api/get-started-with-office-365-management-apis)
- [Portal](https://developer.microsoft.com/en-us/graph)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
