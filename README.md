# Cilium (cilium)

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

Cilium is an open source, cloud native solution for providing, securing, and observing network connectivity between workloads, fueled by the revolutionary kernel technology eBPF. Cilium provides network security, load balancing, and observability for Kubernetes clusters.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cilium/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cilium/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Cloud Native
- eBPF
- Kubernetes
- Networking
- Security

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Cilium API

The Cilium REST API provides access to Cilium daemon and agent endpoints for managing Kubernetes network policy, security, and connectivity. The API is served by the cilium-agent process over a local Unix domain socket and HTTP interface, and covers endpoints, identities, cluster nodes, and health status.

- **Human URL:** [https://docs.cilium.io/en/stable/api/](https://docs.cilium.io/en/stable/api/)
- **Base URL:** `https://localhost/v1`

#### Tags

- eBPF
- Kubernetes
- Networking
- Security

#### Properties

- [Documentation](https://docs.cilium.io/en/stable/api/)
- [OpenAPI](https://github.com/cilium/cilium/blob/main/api/v1/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/cilium-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cilium-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cilium-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Getting Started](https://docs.cilium.io/en/stable/gettingstarted/)
- [Changelog](https://github.com/cilium/cilium/releases)

### Hubble API

The Hubble API is a gRPC-based observability API built on top of Cilium and eBPF that provides deep visibility into network flows, DNS queries, HTTP requests, and service communication within Kubernetes clusters. It exposes Observer and Peer gRPC services for querying flows, nodes, namespaces, and server status across single nodes or entire clusters via Hubble Relay.

- **Human URL:** [https://docs.cilium.io/en/stable/observability/hubble/index.html](https://docs.cilium.io/en/stable/observability/hubble/index.html)

#### Tags

- eBPF
- Kubernetes
- Networking
- Observability

#### Properties

- [Documentation](https://docs.cilium.io/en/stable/observability/hubble/index.html)
- [Reference](https://docs.cilium.io/en/stable/internals/hubble/)
- [AsyncAPI](asyncapi/cilium-hubble-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [GitHub Repository](https://github.com/cilium/hubble)
- [Changelog](https://github.com/cilium/hubble/releases)
- [Postman Collection](collections/cilium-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cilium-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tetragon API

The Tetragon gRPC API provides access to eBPF-based security observability and runtime enforcement capabilities. It enables querying of kernel-level events including process execution, file access, and network activity, and supports defining tracing policies via Kubernetes custom resources for real-time enforcement and event streaming.

- **Human URL:** [https://tetragon.io/docs/reference/grpc-api/](https://tetragon.io/docs/reference/grpc-api/)

#### Tags

- eBPF
- Kubernetes
- Observability
- Security

#### Properties

- [Documentation](https://tetragon.io/docs/reference/grpc-api/)
- [Reference](https://tetragon.io/docs/)
- [GitHub Repository](https://github.com/cilium/tetragon)
- [Getting Started](https://tetragon.io/docs/getting-started/)
- [Changelog](https://github.com/cilium/tetragon/releases)
- [Postman Collection](collections/cilium-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cilium-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cilium Operator API

The Cilium Operator API provides a REST interface for the Cilium operator component, which handles cluster-wide tasks such as garbage collection of Cilium endpoints and identities, node IPAM management, and coordination of cluster mesh operations. It exposes health and status endpoints for operator lifecycle management in Kubernetes deployments.

- **Human URL:** [https://docs.cilium.io/en/stable/internals/](https://docs.cilium.io/en/stable/internals/)
- **Base URL:** `https://localhost/v1`

#### Tags

- eBPF
- Kubernetes
- Networking
- Operations

#### Properties

- [Documentation](https://docs.cilium.io/en/stable/internals/)
- [OpenAPI](https://github.com/cilium/cilium/blob/main/api/v1/operator/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Changelog](https://github.com/cilium/cilium/releases)
- [Postman Collection](collections/cilium-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cilium-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hubble Relay API

The Hubble Relay API is a gRPC service that aggregates and relays network flow data from multiple Hubble agents running across Kubernetes cluster nodes. It provides a single cluster-wide endpoint for the Hubble Observer service, enabling centralized queries of flow data, DNS events, and HTTP metrics from all nodes through Hubble Relay without connecting to each node individually.

- **Human URL:** [https://docs.cilium.io/en/stable/observability/hubble/index.html](https://docs.cilium.io/en/stable/observability/hubble/index.html)

#### Tags

- gRPC
- Kubernetes
- Networking
- Observability

#### Properties

- [Documentation](https://docs.cilium.io/en/stable/observability/hubble/index.html)
- [Reference](https://github.com/cilium/cilium/tree/main/api/v1/relay)
- [GitHub Repository](https://github.com/cilium/cilium)
- [Changelog](https://github.com/cilium/cilium/releases)
- [Postman Collection](collections/cilium-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cilium-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/cilium)
- [Website](https://cilium.io/)
- [Documentation](https://docs.cilium.io/)
- [Getting Started](https://docs.cilium.io/en/stable/gettingstarted/)
- [GitHub Organization](https://github.com/cilium)
- [GitHub Repository](https://github.com/cilium/cilium)
- [Blog](https://cilium.io/blog/)
- [Community](https://cilium.io/get-involved/)
- [Support](https://cilium.io/get-help/)
- [Privacy Policy](https://cilium.io/privacy/)
- [Slack](https://slack.cilium.io/)
- [Changelog](https://github.com/cilium/cilium/releases)
- [YouTube](https://www.youtube.com/@CiliumProject)
- [Terms of Service](https://cilium.io/terms/)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/cilium)
- [J S O N L D Context](json-ld/cilium-context.jsonld)
- [JSON Schema](json-schema/cilium-endpoint-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [AsyncAPI](asyncapi/cilium-hubble-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [OpenAPI](openapi/cilium-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Spectral Rules](spectral/cilium-spectral.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
