# Balena (balena)

Balena is a complete platform for building, deploying, and managing fleets of connected Linux devices. The platform combines balenaOS, balenaEngine, balenaCloud, the balena CLI, and the balena SDK so teams can build container-based device images and continuously deliver them to devices in the field. The balenaCloud REST API exposes device, fleet, release, and organization management using OData-style queries.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/balena/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/balena/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Access:** 3rd-Party

## Tags

- Containers
- Device Management
- Edge
- Embedded Linux
- Fleet Management
- IoT
- OTA
- Provisioning
- Releases

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Balena Cloud API

The balenaCloud REST API is the primary interface to the balena platform. It exposes resources for devices, fleets (applications), releases, environment variables, organizations, and user accounts with bearer-token authentication and OData-style filtering, field selection, and resource expansion.

- **Human URL:** [https://docs.balena.io/reference/api/overview/](https://docs.balena.io/reference/api/overview/)
- **Base URL:** `https://api.balena-cloud.com/v7`

#### Tags

- Device Management
- Fleet Management
- OData
- Releases

#### Properties

- [Documentation](https://docs.balena.io/reference/api/overview/)
- [Authentication](https://docs.balena.io/reference/api/overview/#authentication)
- [Postman Collection](collections/balena.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/balena.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Balena Devices API

Provision, inspect, configure, and remove devices in balenaCloud, including environment variables, tags, status, and OS information.

- **Human URL:** [https://docs.balena.io/reference/api/resources/device/](https://docs.balena.io/reference/api/resources/device/)
- **Base URL:** `https://api.balena-cloud.com/v7`

#### Tags

- Devices
- Provisioning

#### Properties

- [Documentation](https://docs.balena.io/reference/api/resources/device/)
- [Postman Collection](collections/balena.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/balena.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Balena Fleets (Applications) API

Manage balena fleets, formerly known as applications, that group devices and releases for deployment.

- **Human URL:** [https://docs.balena.io/reference/api/resources/application/](https://docs.balena.io/reference/api/resources/application/)
- **Base URL:** `https://api.balena-cloud.com/v7`

#### Tags

- Applications
- Fleet Management

#### Properties

- [Documentation](https://docs.balena.io/reference/api/resources/application/)
- [Postman Collection](collections/balena.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/balena.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Balena Releases API

Manage container-based releases and their assets, pinning, and rollout across a fleet.

- **Human URL:** [https://docs.balena.io/reference/api/resources/release/](https://docs.balena.io/reference/api/resources/release/)
- **Base URL:** `https://api.balena-cloud.com/v7`

#### Tags

- OTA
- Releases

#### Properties

- [Documentation](https://docs.balena.io/reference/api/resources/release/)
- [Postman Collection](collections/balena.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/balena.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Balena Supervisor API

On-device REST API exposed by balena Supervisor for local control of containers, application state, host configuration, reboot, shutdown, and update checks.

- **Human URL:** [https://docs.balena.io/reference/supervisor/supervisor-api/](https://docs.balena.io/reference/supervisor/supervisor-api/)
- **Base URL:** `http://127.0.0.1`

#### Tags

- Devices
- Local API
- Supervisor

#### Properties

- [Documentation](https://docs.balena.io/reference/supervisor/supervisor-api/)
- [Postman Collection](collections/balena.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/balena.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.balena.io/)
- [Developer](https://docs.balena.io/)
- [Documentation](https://docs.balena.io/reference/api/overview/)
- [SDK](https://github.com/balena-io/balena-sdk)
- [C L I](https://github.com/balena-io/balena-cli)
- [Git Hub](https://github.com/balena-io)
- [Blog](https://blog.balena.io/)
- [Pricing](https://www.balena.io/pricing)
- [Status Page](https://status.balena.io/)
- [Support](https://www.balena.io/support)
- [Community](https://forums.balena.io/)
- [Privacy Policy](https://www.balena.io/privacy-policy)
- [Terms of Service](https://www.balena.io/terms-of-service)
- [LinkedIn](https://www.linkedin.com/company/balena-io/)
- [Changelog](https://github.com/balena-io/balena-cli/blob/master/CHANGELOG.md)
- [Integrations](https://www.balena.io/partners)
- [L L Ms Txt](https://docs.balena.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
