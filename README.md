# Scalable Systems

A topic collection focused on APIs, tools, and platforms for designing and operating scalable distributed systems. Covers load balancing, auto-scaling, service discovery, distributed caching, message queues, and the cloud infrastructure APIs that enable systems to handle growth in data, traffic, and complexity.

**Type:** Topic Collection
**Tags:** Auto Scaling, Caching, Cloud Infrastructure, Distributed Systems, High Availability, Infrastructure, Load Balancing, Message Queues, Platform Engineering, Scalable Architecture, Service Discovery

## APIs

### AWS Auto Scaling API
Monitors applications and automatically adjusts capacity across EC2, ECS, Lambda, DynamoDB, and Aurora. Enables defining scaling policies, target tracking, and scheduled scaling.

- **Documentation:** [https://docs.aws.amazon.com/autoscaling/application/APIReference/Welcome.html](https://docs.aws.amazon.com/autoscaling/application/APIReference/Welcome.html)

### HAProxy Data Plane API
Modern REST API for dynamically configuring the HAProxy load balancer without restarting. Enables runtime management of backends, servers, frontends, and ACLs.

- **Documentation:** [https://www.haproxy.com/documentation/dataplaneapi/](https://www.haproxy.com/documentation/dataplaneapi/)
- **OpenAPI:** [https://github.com/haproxytech/dataplaneapi/blob/master/specification/build/haproxy_spec.yaml](https://github.com/haproxytech/dataplaneapi/blob/master/specification/build/haproxy_spec.yaml)
- **GitHub:** [https://github.com/haproxytech/dataplaneapi](https://github.com/haproxytech/dataplaneapi)

### Redis REST API (Upstash)
Serverless Redis-compatible REST API for distributed in-memory caching at scale. Reduces latency and database load in high-traffic systems.

- **Documentation:** [https://upstash.com/docs/redis/features/restapi](https://upstash.com/docs/redis/features/restapi)
- **GitHub:** [https://github.com/redis/redis](https://github.com/redis/redis)

### RabbitMQ Management API
HTTP-based Management API for programmatic administration of queues, exchanges, bindings, vhosts, and consumers. Used for asynchronous task queues and traffic spike absorption.

- **Documentation:** [https://www.rabbitmq.com/management.html](https://www.rabbitmq.com/management.html)
- **OpenAPI:** [https://www.rabbitmq.com/resources/specs/management-api.json](https://www.rabbitmq.com/resources/specs/management-api.json)
- **GitHub:** [https://github.com/rabbitmq/rabbitmq-server](https://github.com/rabbitmq/rabbitmq-server)

### Consul API
HashiCorp Consul REST API providing service discovery, health checking, key-value storage, and service mesh capabilities. Core for service registry and dynamic configuration.

- **Documentation:** [https://developer.hashicorp.com/consul/api-docs](https://developer.hashicorp.com/consul/api-docs)
- **GitHub:** [https://github.com/hashicorp/consul](https://github.com/hashicorp/consul)

### etcd API
Strongly consistent, distributed key-value store gRPC API providing atomic operations, watches, leases, and transactions for distributed coordination and consensus.

- **Documentation:** [https://etcd.io/docs/latest/learning/api/](https://etcd.io/docs/latest/learning/api/)
- **GitHub:** [https://github.com/etcd-io/etcd](https://github.com/etcd-io/etcd)

### Celery Flower API
Real-time monitoring HTTP API for inspecting Celery workers, tasks, queues, and scheduled jobs in distributed task queue deployments.

- **Documentation:** [https://flower.readthedocs.io/en/latest/api.html](https://flower.readthedocs.io/en/latest/api.html)
- **GitHub:** [https://github.com/celery/celery](https://github.com/celery/celery)

### NGINX Plus API
Advanced REST API for runtime configuration and statistics of upstream server groups, virtual servers, and cache zones. Enables dynamic load balancer reconfiguration without reloads.

- **Documentation:** [https://nginx.org/en/docs/http/ngx_http_api_module.html](https://nginx.org/en/docs/http/ngx_http_api_module.html)

## Artifacts

### JSON Schema
- [Load Balancer Schema](json-schema/scalable-systems-load-balancer-schema.json) — Schema for a load balancer configuration including backends, health checks, TLS termination, and sticky sessions.

### JSON Structure
- [Load Balancer Structure](json-structure/scalable-systems-load-balancer-structure.json) — Structural documentation for load balancer configuration.

### JSON-LD Context
- [Scalable Systems Context](json-ld/scalable-systems-context.jsonld) — Linked data context mapping scalable systems vocabulary to schema.org.

### Vocabulary
- [Scalable Systems Vocabulary](vocabulary/scalable-systems-vocabulary.yml) — Domain vocabulary covering CAP Theorem, Eventual Consistency, Sharding, Read Replicas, SLOs, Failover, and more.

### Examples
- [RabbitMQ Queue Configuration](examples/scalable-systems-rabbitmq-queue-example.json) — Example RabbitMQ Management API call for creating a durable queue with dead-letter exchange.

## Common Resources

- [Load Balancing Explained](https://www.nginx.com/resources/glossary/load-balancing/)
- [AWS Auto Scaling Features](https://aws.amazon.com/autoscaling/features/)
- [Redis Scaling Guide](https://redis.io/docs/manual/scaling/)
- [Service Discovery with Consul](https://www.consul.io/use-cases/service-discovery-and-health-checking)
- [Scalable Systems in Distributed Computing](https://geeksforgeeks.org/distributed-systems/what-is-scalable-system-in-distributed-system/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
