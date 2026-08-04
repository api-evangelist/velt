# Velt (velt)

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

Velt is a real-time collaboration platform delivered primarily as a client SDK (React components and framework wrappers) for adding presence, live cursors, comments, notifications, huddles, recordings, and live selection to applications. Its server-side surface is the Velt Data (REST) API at api.velt.dev plus signed, retried webhooks, letting backends read and write comments, users, organizations, folders, documents, notifications, and user groups programmatically.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/velt/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/velt/refs/heads/main/apis.yml)

## Tags

- Real-Time Collaboration
- Comments
- Presence
- Notifications
- SDK
- Webhooks

## Timestamps

- **Created:** 2026-07-01
- **Modified:** 2026-07-01

## APIs

### Velt Comments API

Server-side CRUD over comment threads and their annotations - add, get, update, and delete comments and comment annotations, and retrieve annotation counts - scoped by organization and document. Comments are the collaboration data the client SDK renders in-app.

- **Human URL:** [https://velt.dev/docs/api-reference/rest-apis](https://velt.dev/docs/api-reference/rest-apis)
- **Base URL:** `https://api.velt.dev/v2`

#### Tags

- Comments
- Annotations
- Collaboration

#### Properties

- [Documentation](https://velt.dev/docs/api-reference/rest-apis)
- [API Reference](https://velt.dev/docs/api-reference/rest-apis/v2/comments/get-comments)
- [OpenAPI](openapi/velt-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/velt.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/velt.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Velt Users API

Add, get, update, and delete the end users that participate in collaboration, plus user-group membership operations, so backends can keep Velt identities in sync with the host application's user directory.

- **Human URL:** [https://velt.dev/docs/api-reference/rest-apis](https://velt.dev/docs/api-reference/rest-apis)
- **Base URL:** `https://api.velt.dev/v2`

#### Tags

- Users
- Identity
- Collaboration

#### Properties

- [Documentation](https://velt.dev/docs/api-reference/rest-apis)
- [OpenAPI](openapi/velt-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/velt.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/velt.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Velt Organizations API

Manage organizations - the top-level tenancy boundary in Velt - with add, get, update, delete, and enable/disable operations that partition collaboration data and access across teams and customers.

- **Human URL:** [https://velt.dev/docs/api-reference/rest-apis](https://velt.dev/docs/api-reference/rest-apis)
- **Base URL:** `https://api.velt.dev/v2`

#### Tags

- Organizations
- Tenancy
- Access

#### Properties

- [Documentation](https://velt.dev/docs/api-reference/rest-apis)
- [OpenAPI](openapi/velt-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/velt.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/velt.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Velt Documents API

Create and manage documents and folders - the addressable surfaces that collaboration is attached to - including add, get, update, move, migrate, delete, access-control, and disabled-state operations.

- **Human URL:** [https://velt.dev/docs/api-reference/rest-apis](https://velt.dev/docs/api-reference/rest-apis)
- **Base URL:** `https://api.velt.dev/v2`

#### Tags

- Documents
- Folders
- Access Control

#### Properties

- [Documentation](https://velt.dev/docs/api-reference/rest-apis)
- [OpenAPI](openapi/velt-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/velt.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/velt.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Velt Notifications API

Add, get, update, and delete notifications and read or set per-user and per-organization notification config (inbox and email delivery), driving the notification and inbox components rendered by the SDK.

- **Human URL:** [https://velt.dev/docs/api-reference/rest-apis/v2/notifications/get-config](https://velt.dev/docs/api-reference/rest-apis/v2/notifications/get-config)
- **Base URL:** `https://api.velt.dev/v2`

#### Tags

- Notifications
- Inbox
- Email

#### Properties

- [Documentation](https://velt.dev/docs/api-reference/rest-apis)
- [API Reference](https://velt.dev/docs/api-reference/rest-apis/v2/notifications/get-config)
- [OpenAPI](openapi/velt-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/velt.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/velt.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Velt Webhooks API

Configure advanced webhook endpoints and subscribe to collaboration events (for example newly-added and status-change actions on comments) generated by humans and agents. Deliveries are HMAC-signed, verified via the signature header, and retried with exponential backoff.

- **Human URL:** [https://velt.dev/docs/webhooks/advanced](https://velt.dev/docs/webhooks/advanced)
- **Base URL:** `https://api.velt.dev/v2`

#### Tags

- Webhooks
- Events
- HMAC

#### Properties

- [Documentation](https://velt.dev/docs/webhooks/advanced)
- [OpenAPI](openapi/velt-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/velt.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/velt.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Velt Auth Tokens API

Workspace-level management of API keys and auth tokens - create, get, and update API keys, read and update API key config, reset auth tokens, and generate the short-lived tokens and signatures that authorize SDK and Data API calls.

- **Human URL:** [https://velt.dev/docs/api-reference/rest-apis](https://velt.dev/docs/api-reference/rest-apis)
- **Base URL:** `https://api.velt.dev/v2`

#### Tags

- Authentication
- API Keys
- Tokens

#### Properties

- [Documentation](https://velt.dev/docs/api-reference/rest-apis)
- [OpenAPI](openapi/velt-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/velt.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/velt.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/veltdev)
- [LinkedIn](https://www.linkedin.com/company/velt-dev)
- [Website](https://velt.dev/)
- [Documentation](https://velt.dev/docs)
- [Plans](plans/velt-plans-pricing.yml)
- [Rate Limits](rate-limits/velt-rate-limits.yml)
- [Fin Ops](finops/velt-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
