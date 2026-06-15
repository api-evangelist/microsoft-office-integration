# Microsoft Office Integration (microsoft-office-integration)

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
