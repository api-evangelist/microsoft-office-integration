# Microsoft Office Integration (microsoft-office-integration)
APIs for Microsoft Office Integration, connecting Microsoft Office components and systems for seamless data exchange and end-to-end workflows across multiple technologies and platforms. The Office 365 Management APIs provide a single extensibility platform for management tasks including service communications, security, compliance, reporting, and auditing, using common industry-standard approaches including OAuth v2, OData v4, and JSON.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/microsoft-office-integration/refs/heads/main/apis.yml)

## Scope

- **Type:** Index 
- **Position:** Consuming 
- **Access:** 3rd-Party 

## Tags:

 - Microsoft Office Integration, Microsoft 365, Office 365

## Timestamps

- **Created:** 2025-01-01 
- **Modified:** 2026-04-28 

## APIs

### Microsoft Office 365 Management Activity API
The Office 365 Management Activity API provides information about various user, admin, system, and policy actions and events from Office 365 and Microsoft Entra activity logs. It enables customers and partners to create or enhance operations, security, and compliance-monitoring solutions. The API supports subscription management, content retrieval, webhook notifications, and DLP sensitive type lookups across content types including Azure AD, Exchange, SharePoint, and General audit logs.

**Human URL:** [https://learn.microsoft.com/en-us/office/office-365-management-api/office-365-management-activity-api-reference](https://learn.microsoft.com/en-us/office/office-365-management-api/office-365-management-activity-api-reference)


#### Tags:

 - Office 365, Auditing, Compliance, Security

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/office/office-365-management-api/office-365-management-activity-api-reference)
- [OpenAPI](openapi/microsoft-office-management-activity-api-openapi.yml)
- [JSONSchema](json-schema/subscription.json)
- [JSONSchema](json-schema/activity-record.json)
- [JSONSchema](json-schema/content-blob.json)
- [JSONLD](json-ld/microsoft-office-integration-context.jsonld)

### Microsoft Office 365 Service Communications API
The Office 365 Service Communications API provides tenant administrators and partners with real-time service health information and Message Center communications. It enables access to the list of subscribed services, current and historical service status, incident details, and planned maintenance notifications for Office 365, Yammer, Dynamics CRM, and Microsoft Intune cloud services.

**Human URL:** [https://learn.microsoft.com/en-us/office/office-365-management-api/office-365-service-communications-api-reference](https://learn.microsoft.com/en-us/office/office-365-management-api/office-365-service-communications-api-reference)


#### Tags:

 - Office 365, Service Health, Monitoring, Incidents

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/office/office-365-management-api/office-365-service-communications-api-reference)
- [OpenAPI](openapi/microsoft-office-service-communications-api-openapi.yml)
- [JSONSchema](json-schema/service.json)
- [JSONSchema](json-schema/workload-status.json)
- [JSONSchema](json-schema/message.json)
- [JSONLD](json-ld/microsoft-office-integration-context.jsonld)

## Common Properties

- [Documentation](https://learn.microsoft.com/en-us/office/office-365-management-api/)
- [Documentation](https://learn.microsoft.com/en-us/graph/overview)
- [GettingStarted](https://learn.microsoft.com/en-us/office/office-365-management-api/get-started-with-office-365-management-apis)
- [Portal](https://developer.microsoft.com/en-us/graph)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
