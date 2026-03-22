# Cilium (cilium)
Cilium is an open source, cloud native solution for providing, securing, and observing network connectivity between workloads, fueled by the revolutionary kernel technology eBPF. Cilium provides network security, load balancing, and observability for Kubernetes clusters.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/cilium/refs/heads/main/apis.yml)

## Scope

- **Type:** Index 
- **Position:** Consuming 
- **Access:** 3rd-Party 

## Tags:

 - Kubernetes, Networking, Security, eBPF, Cloud Native

## Timestamps

- **Created:** 2026-03-16 
- **Modified:** 2026-03-18 

## APIs

### Cilium API
The Cilium REST API provides access to Cilium daemon and agent endpoints for managing Kubernetes network policy, security, and connectivity. The API is served by the cilium-agent process over a local Unix domain socket and HTTP interface, and covers endpoints, identities, cluster nodes, and health status.

**Human URL:** [https://docs.cilium.io/en/stable/api/](https://docs.cilium.io/en/stable/api/)


#### Tags:

 - Kubernetes, Networking, eBPF, Security

#### Properties

- [Documentation](https://docs.cilium.io/en/stable/api/)
- [OpenAPI](https://github.com/cilium/cilium/blob/main/api/v1/openapi.yaml)
- [OpenAPI](openapi/cilium-api-openapi.yml)
- [Getting Started](https://docs.cilium.io/en/stable/gettingstarted/)
- [Change Log](https://github.com/cilium/cilium/releases)

### Hubble API
The Hubble API is a gRPC-based observability API built on top of Cilium and eBPF that provides deep visibility into network flows, DNS queries, HTTP requests, and service communication within Kubernetes clusters. It exposes Observer and Peer gRPC services for querying flows, nodes, namespaces, and server status across single nodes or entire clusters via Hubble Relay.

**Human URL:** [https://docs.cilium.io/en/stable/observability/hubble/index.html](https://docs.cilium.io/en/stable/observability/hubble/index.html)


#### Tags:

 - Observability, Networking, Kubernetes, eBPF

#### Properties

- [Documentation](https://docs.cilium.io/en/stable/observability/hubble/index.html)
- [Reference](https://docs.cilium.io/en/stable/internals/hubble/)
- [AsyncAPI](asyncapi/cilium-hubble-asyncapi.yml)
- [GitHubRepository](https://github.com/cilium/hubble)
- [Change Log](https://github.com/cilium/hubble/releases)

### Tetragon API
The Tetragon gRPC API provides access to eBPF-based security observability and runtime enforcement capabilities. It enables querying of kernel-level events including process execution, file access, and network activity, and supports defining tracing policies via Kubernetes custom resources for real-time enforcement and event streaming.

**Human URL:** [https://tetragon.io/docs/reference/grpc-api/](https://tetragon.io/docs/reference/grpc-api/)


#### Tags:

 - Security, Observability, Kubernetes, eBPF

#### Properties

- [Documentation](https://tetragon.io/docs/reference/grpc-api/)
- [Reference](https://tetragon.io/docs/)
- [GitHubRepository](https://github.com/cilium/tetragon)
- [Getting Started](https://tetragon.io/docs/getting-started/)
- [Change Log](https://github.com/cilium/tetragon/releases)

### Cilium Operator API
The Cilium Operator API provides a REST interface for the Cilium operator component, which handles cluster-wide tasks such as garbage collection of Cilium endpoints and identities, node IPAM management, and coordination of cluster mesh operations. It exposes health and status endpoints for operator lifecycle management in Kubernetes deployments.

**Human URL:** [https://docs.cilium.io/en/stable/internals/](https://docs.cilium.io/en/stable/internals/)


#### Tags:

 - Kubernetes, Networking, Operations, eBPF

#### Properties

- [Documentation](https://docs.cilium.io/en/stable/internals/)
- [OpenAPI](https://github.com/cilium/cilium/blob/main/api/v1/operator/openapi.yaml)
- [Change Log](https://github.com/cilium/cilium/releases)

### Hubble Relay API
The Hubble Relay API is a gRPC service that aggregates and relays network flow data from multiple Hubble agents running across Kubernetes cluster nodes. It provides a single cluster-wide endpoint for the Hubble Observer service, enabling centralized queries of flow data, DNS events, and HTTP metrics from all nodes through Hubble Relay without connecting to each node individually.

**Human URL:** [https://docs.cilium.io/en/stable/observability/hubble/index.html](https://docs.cilium.io/en/stable/observability/hubble/index.html)


#### Tags:

 - Observability, Networking, Kubernetes, gRPC

#### Properties

- [Documentation](https://docs.cilium.io/en/stable/observability/hubble/index.html)
- [Reference](https://github.com/cilium/cilium/tree/main/api/v1/relay)
- [GitHubRepository](https://github.com/cilium/cilium)
- [Change Log](https://github.com/cilium/cilium/releases)

## Common Properties

- [JSON-LD](json-ld/cilium-context.jsonld)
- [JSONSchema](json-schema/cilium-endpoint-schema.json)
- [Website](https://cilium.io/)
- [Documentation](https://docs.cilium.io/)
- [Getting Started](https://docs.cilium.io/en/stable/gettingstarted/)
- [GitHub Organization](https://github.com/cilium)
- [GitHubRepository](https://github.com/cilium/cilium)
- [Blog](https://cilium.io/blog/)
- [Community](https://cilium.io/get-involved/)
- [Support](https://cilium.io/get-help/)
- [Privacy Policy](https://cilium.io/privacy/)
- [Slack](https://slack.cilium.io/)
- [Change Log](https://github.com/cilium/cilium/releases)
- [YouTube](https://www.youtube.com/@CiliumProject)
- [Terms of Service](https://cilium.io/terms/)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/cilium)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
