# Balena (balena)

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
