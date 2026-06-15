# Scalable Systems (scalable-systems)

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
