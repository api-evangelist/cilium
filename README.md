# Cilium (cilium)

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
