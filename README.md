# Creatomate (creatomate)

Creatomate is a media-automation platform that generates videos and images at scale from reusable templates. Its REST API renders MP4/GIF/image output by applying per-element modifications to a template, runs asynchronously, and notifies callers via polling or webhooks. Billing is credit-based per rendered output.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/creatomate/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/creatomate/refs/heads/main/apis.yml)

## Tags

- Media
- Video Generation
- Image Generation
- Automation
- Templates
- Rendering

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Creatomate Renders API

Create one or more renders from a template ID, source, or template tags, applying per-element modifications, then poll for status or receive a webhook when each render succeeds or fails. Output is MP4, GIF, JPG, or PNG hosted by Creatomate.

- **Human URL:** [https://creatomate.com/docs/api/reference/introduction](https://creatomate.com/docs/api/reference/introduction)
- **Base URL:** `https://api.creatomate.com/v1`

#### Tags

- Renders
- Video
- Image
- Async

#### Properties

- [Documentation](https://creatomate.com/docs/api/quick-start/introduction)
- [API Reference](https://creatomate.com/docs/api/reference/create-a-render)
- [OpenAPI](openapi/creatomate-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/creatomate.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/creatomate.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Creatomate Templates API

List the templates in a project with their metadata and tags, and fetch a single template by ID including its RenderScript source, which describes the named elements available for modification at render time.

- **Human URL:** [https://creatomate.com/docs/api/reference/get-all-templates-in-a-project](https://creatomate.com/docs/api/reference/get-all-templates-in-a-project)
- **Base URL:** `https://api.creatomate.com/v1`

#### Tags

- Templates
- Catalog
- Metadata

#### Properties

- [Documentation](https://creatomate.com/docs/api/reference/get-all-templates-in-a-project)
- [API Reference](https://creatomate.com/docs/api/reference/get-a-template-by-its-id)
- [OpenAPI](openapi/creatomate-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/creatomate.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/creatomate.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Creatomate Webhooks

Per-render callback delivery. Supply webhook_url when creating a render and Creatomate POSTs the full Render object (including any caller-supplied metadata) to that URL once the render reaches a terminal succeeded or failed state.

- **Human URL:** [https://creatomate.com/docs/api/rest-api/webhooks](https://creatomate.com/docs/api/rest-api/webhooks)
- **Base URL:** `https://api.creatomate.com/v1`

#### Tags

- Webhooks
- Async
- Notifications

#### Properties

- [Documentation](https://creatomate.com/docs/api/rest-api/webhooks)
- [API Reference](https://creatomate.com/docs/api/reference/set-up-a-webhook)
- [OpenAPI](openapi/creatomate-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [GitHub Organization](https://github.com/creatomate)
- [LinkedIn](https://www.linkedin.com/company/creatomate)
- [Website](https://creatomate.com/)
- [Documentation](https://creatomate.com/docs/api/quick-start/introduction)
- [Plans](plans/creatomate-plans-pricing.yml)
- [Rate Limits](rate-limits/creatomate-rate-limits.yml)
- [Fin Ops](finops/creatomate-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
