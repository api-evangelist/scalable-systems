# Scalable Systems (scalable-systems)

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

A topic collection focused on APIs, tools, and platforms for designing and operating scalable distributed systems. Covers load balancing, auto-scaling, service discovery, distributed caching, message queues, and the cloud infrastructure APIs that enable systems to handle growth in data, traffic, and complexity. Relevant to site reliability engineers, infrastructure architects, and platform engineers responsible for operating high-scale production environments.

## Scope

- **Type:** Index

## Tags

- Auto Scaling
- Caching
- Cloud Infrastructure
- Distributed Systems
- High Availability
- Infrastructure
- Load Balancing
- Message Queues
- Platform Engineering
- Scalable Architecture
- Service Discovery

## Timestamps

- **Created:** 2025-01-15
- **Modified:** 2026-05-02

## APIs

### AWS Auto Scaling API

AWS Auto Scaling monitors applications and automatically adjusts capacity across multiple AWS resources including EC2, ECS, Lambda, DynamoDB, and Aurora. The API enables defining scaling policies, target tracking, and scheduled scaling for systems that must respond to variable load.

- **Human URL:** [https://docs.aws.amazon.com/autoscaling/application/APIReference/Welcome.html](https://docs.aws.amazon.com/autoscaling/application/APIReference/Welcome.html)

#### Tags

- Auto Scaling
- AWS
- Cloud Infrastructure
- Scalable Architecture

#### Properties

- [Documentation](https://docs.aws.amazon.com/autoscaling/application/APIReference/Welcome.html)
- [Postman Collection](collections/scalable-systems.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalable-systems.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HAProxy Data Plane API

HAProxy's Data Plane API is a modern REST API for dynamically configuring the HAProxy load balancer without restarting. Enables runtime management of backends, servers, frontends, and ACLs in high-availability deployments.

- **Human URL:** [https://www.haproxy.com/documentation/dataplaneapi/](https://www.haproxy.com/documentation/dataplaneapi/)

#### Tags

- High Availability
- Load Balancing
- Proxy
- Traffic Management

#### Properties

- [Documentation](https://www.haproxy.com/documentation/dataplaneapi/)
- [OpenAPI](https://github.com/haproxytech/dataplaneapi/blob/master/specification/build/haproxy_spec.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Git Hub](https://github.com/haproxytech/dataplaneapi)
- [Postman Collection](collections/scalable-systems.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalable-systems.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Redis REST API (Upstash)

Redis is the dominant distributed in-memory cache and data structure store used to reduce latency and database load in scalable systems. Upstash provides a serverless Redis-compatible REST API for low-latency caching at scale.

- **Human URL:** [https://upstash.com/docs/redis/features/restapi](https://upstash.com/docs/redis/features/restapi)

#### Tags

- Caching
- Distributed Systems
- In-Memory
- Low Latency

#### Properties

- [Documentation](https://upstash.com/docs/redis/features/restapi)
- [Git Hub](https://github.com/redis/redis)
- [Postman Collection](collections/scalable-systems.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalable-systems.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RabbitMQ Management API

RabbitMQ's HTTP-based Management API enables programmatic administration of queues, exchanges, bindings, vhosts, and consumers. RabbitMQ is widely used for asynchronous task queues, decoupling services, and absorbing traffic spikes in scalable systems.

- **Human URL:** [https://www.rabbitmq.com/management.html](https://www.rabbitmq.com/management.html)

#### Tags

- Asynchronous
- Decoupling
- Message Queues
- Messaging

#### Properties

- [Documentation](https://www.rabbitmq.com/management.html)
- [OpenAPI](https://www.rabbitmq.com/resources/specs/management-api.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Git Hub](https://github.com/rabbitmq/rabbitmq-server)
- [Postman Collection](collections/scalable-systems.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalable-systems.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Consul API

HashiCorp Consul provides service discovery, health checking, key-value storage, and service mesh capabilities via a comprehensive REST API. Core component for service registry and dynamic configuration in scalable distributed systems.

- **Human URL:** [https://developer.hashicorp.com/consul/api-docs](https://developer.hashicorp.com/consul/api-docs)

#### Tags

- Configuration Management
- High Availability
- Service Discovery
- Service Mesh

#### Properties

- [Documentation](https://developer.hashicorp.com/consul/api-docs)
- [Git Hub](https://github.com/hashicorp/consul)
- [Postman Collection](collections/scalable-systems.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalable-systems.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### etcd API

etcd is a strongly consistent, distributed key-value store used as the backing store for Kubernetes and many distributed systems. Its gRPC API provides atomic operations, watches, leases, and transactions for distributed coordination and consensus.

- **Human URL:** [https://etcd.io/docs/latest/learning/api/](https://etcd.io/docs/latest/learning/api/)

#### Tags

- Configuration Management
- Distributed Systems
- High Availability
- Kubernetes

#### Properties

- [Documentation](https://etcd.io/docs/latest/learning/api/)
- [Git Hub](https://github.com/etcd-io/etcd)
- [Postman Collection](collections/scalable-systems.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalable-systems.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Celery Flower API

Celery is a distributed task queue for Python applications. Flower is Celery's real-time monitoring tool that exposes an HTTP API for inspecting workers, tasks, queues, and scheduled jobs in production systems.

- **Human URL:** [https://flower.readthedocs.io/en/latest/api.html](https://flower.readthedocs.io/en/latest/api.html)

#### Tags

- Asynchronous
- Distributed Systems
- Message Queues
- Task Queue

#### Properties

- [Documentation](https://flower.readthedocs.io/en/latest/api.html)
- [Git Hub](https://github.com/celery/celery)
- [Postman Collection](collections/scalable-systems.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalable-systems.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NGINX Plus API

NGINX Plus provides an advanced REST API for runtime configuration and statistics of upstream server groups, virtual servers, and cache zones. Enables dynamic load balancer reconfiguration and real-time traffic monitoring without reloads.

- **Human URL:** [https://nginx.org/en/docs/http/ngx_http_api_module.html](https://nginx.org/en/docs/http/ngx_http_api_module.html)

#### Tags

- HTTP
- High Performance
- Load Balancing
- Traffic Management

#### Properties

- [Documentation](https://nginx.org/en/docs/http/ngx_http_api_module.html)
- [Postman Collection](collections/scalable-systems.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalable-systems.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Guide](https://www.nginx.com/resources/glossary/load-balancing/)
- [Guide](https://aws.amazon.com/autoscaling/features/)
- [Guide](https://redis.io/docs/manual/scaling/)
- [Guide](https://www.consul.io/use-cases/service-discovery-and-health-checking)
- [Guide](https://geeksforgeeks.org/distributed-systems/what-is-scalable-system-in-distributed-system/)
- [JSON Schema](https://github.com/api-evangelist/scalable-systems/blob/main/json-schema/scalable-systems-load-balancer-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](https://github.com/api-evangelist/scalable-systems/blob/main/json-structure/scalable-systems-load-balancer-structure.json)
- [J S O N L D Context](https://github.com/api-evangelist/scalable-systems/blob/main/json-ld/scalable-systems-context.jsonld)
- [Vocabulary](https://github.com/api-evangelist/scalable-systems/blob/main/vocabulary/scalable-systems-vocabulary.yml)
- [Examples](https://github.com/api-evangelist/scalable-systems/blob/main/examples/scalable-systems-rabbitmq-queue-example.json)
- [Examples](https://github.com/api-evangelist/scalable-systems/blob/main/examples/scalable-systems-consul-service-registration-example.json)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
