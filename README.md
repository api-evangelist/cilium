# Cilium

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

**Areas:** Cloud-Native · eBPF · Kubernetes · Networking · Security

## Cilium on APIs.io

Everything profiled for Cilium is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/cilium/](https://apis.io/providers/cilium/)** — or go straight to one of the APIs or properties below.

### APIs (11)

- [Hubble API](https://apis.io/apis/cilium/hubble-api/) — The Hubble API is a gRPC-based observability API built on top of Cilium and eBPF that provides deep visibility into network flows, DNS queries, HTTP…
- [Tetragon API](https://apis.io/apis/cilium/tetragon-api/) — The Tetragon gRPC API provides access to eBPF-based security observability and runtime enforcement capabilities. It enables querying of kernel-level events…
- [Hubble Relay API](https://apis.io/apis/cilium/hubble-relay-api/) — The Hubble Relay API is a gRPC service that aggregates and relays network flow data from multiple Hubble agents running across Kubernetes cluster nodes. It…
- [Cilium BGP API](https://apis.io/apis/cilium/cilium-bgp-api/) — BGP control plane peers, routes, and route policies
- [Cilium Daemon API](https://apis.io/apis/cilium/cilium-daemon-api/) — Cilium daemon configuration, health, and cluster management
- [Cilium Endpoint API](https://apis.io/apis/cilium/cilium-endpoint-api/) — Endpoint lifecycle management, configuration, and status
- [Cilium IPAM API](https://apis.io/apis/cilium/cilium-ipam-api/) — IP address management and allocation
- [Cilium Lrp API](https://apis.io/apis/cilium/cilium-lrp-api/) — The Lrp API from Cilium — 1 operation(s) for lrp.
- [Cilium Policy API](https://apis.io/apis/cilium/cilium-policy-api/) — Network policy, security identities, and FQDN/DNS policy
- [Cilium Prefilter API](https://apis.io/apis/cilium/cilium-prefilter-api/) — XDP prefilter CIDR management
- [Cilium Service API](https://apis.io/apis/cilium/cilium-service-api/) — The Service API from Cilium — 2 operation(s) for service.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Cilium Hubble Events](https://apis.io/asyncapis/cilium/cilium-hubble-asyncapi/)

#### Event channels (5)

Individual events and webhooks the provider emits.

- [/observer.Observer/GetAgentEvents](https://apis.io/channels/cilium/observer-observer-getagentevents/)
- [/observer.Observer/GetDebugEvents](https://apis.io/channels/cilium/observer-observer-getdebugevents/)
- [/observer.Observer/GetFlows](https://apis.io/channels/cilium/observer-observer-getflows/)
- [/observer.Observer/GetNamespaces](https://apis.io/channels/cilium/observer-observer-getnamespaces/)
- [/observer.Observer/GetNodes](https://apis.io/channels/cilium/observer-observer-getnodes/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Cilium Agentic Access](https://apis.io/agentic-access/cilium/cilium-agentic-access/)

#### JSON Schema (1)

The data models the API reads and writes.

- [Cilium Endpoint](https://apis.io/schemas/cilium/cilium-endpoint/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Cilium Context](https://apis.io/jsonld/cilium/cilium-context/)

#### Collections (9)

Postman and Open Collection request collections.

- [Cilium API](https://apis.io/collections/cilium/open-cilium-api/)
- [Cilium BGP API](https://apis.io/collections/cilium/open-cilium-bgp-api/)
- [Cilium BGP Daemon API](https://apis.io/collections/cilium/open-cilium-daemon-api/)
- [Cilium BGP Endpoint API](https://apis.io/collections/cilium/open-cilium-endpoint-api/)
- [Cilium BGP IPAM API](https://apis.io/collections/cilium/open-cilium-ipam-api/)
- [Cilium BGP Lrp API](https://apis.io/collections/cilium/open-cilium-lrp-api/)
- [Cilium BGP Policy API](https://apis.io/collections/cilium/open-cilium-policy-api/)
- [Cilium BGP Prefilter API](https://apis.io/collections/cilium/open-cilium-prefilter-api/)
- [Cilium BGP Service API](https://apis.io/collections/cilium/open-cilium-service-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Cilium — asyncapi rules](https://apis.io/rules/cilium/cilium-asyncapi-spectral-rules/)
- [Cilium — jsonschema rules](https://apis.io/rules/cilium/cilium-jsonschema-spectral-rules/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Cilium Domain Security](https://apis.io/security/cilium/cilium-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Cilium Plans Pricing](https://apis.io/plans/cilium/cilium-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Cilium Rate Limits](https://apis.io/rate-limits/cilium/cilium-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Cilium Finops](https://apis.io/finops/cilium/cilium-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://cilium.io/)
- [Documentation](https://docs.cilium.io/)
- [Getting started](https://docs.cilium.io/en/stable/gettingstarted/)
- [Support](https://cilium.io/get-help/)
- [Changelog](https://github.com/cilium/cilium/releases)
- [Blog](https://cilium.io/blog/)
- [Terms of service](https://cilium.io/terms/)
- [Privacy policy](https://cilium.io/privacy/)
- [GitHub](https://github.com/cilium)

## API Evangelist rating

**Kin Score 42.6** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 54.6 |
| Contract governance | 13.6 |
| Operational transparency | 36.8 |
| Developer ergonomics | 35.7 |
| Access clarity | 5.3 |

**Agent readiness 23.0** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 10.8** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/cilium/](https://apis.io/providers/cilium/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Cilium: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/cilium/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
