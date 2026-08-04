# Microsoft Excel (Advanced) (microsoft-excel-advanced)

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

Advanced automation and integration APIs for Microsoft Excel, enabling programmatic access to spreadsheet data, formulas, charts, and automation capabilities through Microsoft Graph, Office Scripts, JavaScript add-ins, custom functions, OneDrive REST endpoints, and Power Automate connectors.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/microsoft-excel-advanced/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/microsoft-excel-advanced/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Automation
- Business Intelligence
- Data Analysis
- Office
- Spreadsheets

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-28

## APIs

### Microsoft Graph Excel API

REST API for reading and writing Excel workbook data through Microsoft Graph.

- **Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/excel](https://learn.microsoft.com/en-us/graph/api/resources/excel)
- **Base URL:** `https://graph.microsoft.com/v1.0`

#### Tags

- Cloud
- REST
- Workbooks
- Worksheets

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/api/resources/excel)
- [OpenAPI](https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://learn.microsoft.com/en-us/graph/auth/)
- [Quick Start](https://learn.microsoft.com/en-us/graph/api/resources/excel#get-started)
- [Postman Collection](collections/microsoft-excel-advanced.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-excel-advanced.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Office Scripts API

TypeScript-based automation API for Excel on the web and desktop.

- **Human URL:** [https://learn.microsoft.com/en-us/office/dev/scripts/](https://learn.microsoft.com/en-us/office/dev/scripts/)
- **Base URL:** `https://script.office.com`

#### Tags

- Automation
- Power-Automate
- Scripting
- Typescript

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/office/dev/scripts/overview/excel)
- [Samples](https://learn.microsoft.com/en-us/office/dev/scripts/resources/samples/)
- [API Reference](https://learn.microsoft.com/en-us/javascript/api/office-scripts/overview)
- [Tutorials](https://learn.microsoft.com/en-us/office/dev/scripts/tutorials/excel-tutorial)
- [Postman Collection](collections/microsoft-excel-advanced.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-excel-advanced.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Excel JavaScript API

JavaScript API for building Excel add-ins and extensions.

- **Human URL:** [https://learn.microsoft.com/en-us/office/dev/add-ins/reference/overview/excel-add-ins-reference-overview](https://learn.microsoft.com/en-us/office/dev/add-ins/reference/overview/excel-add-ins-reference-overview)
- **Base URL:** `https://appsforoffice.microsoft.com`

#### Tags

- Add-Ins
- Extensions
- Javascript
- Office-Js

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/office/dev/add-ins/excel/)
- [API Reference](https://learn.microsoft.com/en-us/javascript/api/excel)
- [Samples](https://github.com/OfficeDev/Office-Add-in-samples)
- [Quick  Start](https://learn.microsoft.com/en-us/office/dev/add-ins/quickstarts/excel-quickstart-jquery)
- [C D N](https://appsforoffice.microsoft.com/lib/1/hosted/office.js)
- [Postman Collection](collections/microsoft-excel-advanced.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-excel-advanced.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Excel Custom Functions API

API for creating custom functions in Excel using JavaScript.

- **Human URL:** [https://learn.microsoft.com/en-us/office/dev/add-ins/excel/custom-functions-overview](https://learn.microsoft.com/en-us/office/dev/add-ins/excel/custom-functions-overview)

#### Tags

- Calculations
- Custom-Functions
- Formulas
- Udf

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/office/dev/add-ins/excel/custom-functions-overview)
- [Tutorial](https://learn.microsoft.com/en-us/office/dev/add-ins/tutorials/excel-tutorial-create-custom-functions)
- [Best  Practices](https://learn.microsoft.com/en-us/office/dev/add-ins/excel/custom-functions-best-practices)
- [Postman Collection](collections/microsoft-excel-advanced.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-excel-advanced.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Excel REST API (OneDrive)

REST API for accessing Excel files stored in OneDrive and SharePoint.

- **Human URL:** [https://learn.microsoft.com/en-us/onedrive/developer/rest-api/](https://learn.microsoft.com/en-us/onedrive/developer/rest-api/)
- **Base URL:** `https://graph.microsoft.com/v1.0/me/drive`

#### Tags

- Cloud-Storage
- Onedrive
- REST
- Sharepoint

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/onedrive/developer/rest-api/api/driveitem_get)
- [API Reference](https://learn.microsoft.com/en-us/graph/api/resources/driveitem)
- [Postman Collection](collections/microsoft-excel-advanced.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-excel-advanced.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Power Automate Excel Connector

Pre-built connector for automating Excel workflows in Power Automate.

- **Human URL:** [https://learn.microsoft.com/en-us/connectors/excelonlinebusiness/](https://learn.microsoft.com/en-us/connectors/excelonlinebusiness/)

#### Tags

- Connector
- Low-Code
- Power-Automate
- Workflow

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/connectors/excelonlinebusiness/)
- [Actions  Reference](https://learn.microsoft.com/en-us/connectors/excelonlinebusiness/#actions)
- [Triggers  Reference](https://learn.microsoft.com/en-us/connectors/excelonlinebusiness/#triggers)
- [Postman Collection](collections/microsoft-excel-advanced.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-excel-advanced.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://developer.microsoft.com/en-us/microsoft-365)
- [Authentication  Guide](https://learn.microsoft.com/en-us/azure/active-directory/develop/)
- [S D Ks](https://learn.microsoft.com/en-us/graph/sdks/sdks-overview)
- [Status Page](https://status.cloud.microsoft/)
- [Terms of Service](https://www.microsoft.com/en-us/legal/terms-of-use)
- [Privacy Policy](https://privacy.microsoft.com/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
