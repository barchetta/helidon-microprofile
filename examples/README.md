# Helidon MicroProfile Examples

Build all examples from this directory with `mvn clean install`.
Each example has its own build and run instructions.

## Getting started

- [Hello World](hello-world/README.md): implicit and explicit server startup. Start with the implicit example.

## Server basics

- [Static content](static-content/README.md): serve static files alongside REST resources.
- [Multiport](multiport/README.md): separate public, private, and observability ports.
- [Multipart](multipart/README.md): upload and download files.
- [Threads](threads/README.md): virtual threads and a platform-thread executor.

## Beyond the basics

- [Bean validation](bean-validation/README.md): validate REST request data.
- [GraphQL](graphql/README.md): a task management API.
- [gRPC](grpc/README.md): a gRPC service and client proxy.
- [JSON Patch](json-patch/README.md): update resources using JSON Patch.
- [OpenAPI](openapi/README.md): basic documentation and expanded Jandex indexing.
- [WebSocket](websocket/README.md): WebSocket messaging alongside REST endpoints.

## Security

- [Application security](security/multiple-applications/README.md): role-based access across JAX-RS applications.
- [OIDC](security/oidc/README.md): OpenID Connect authentication; requires an identity provider and client configuration.
- [IDCS](security/idcs/README.md): Oracle Identity Cloud Service integration; requires a configured identity tenant.
- [TLS](tls/README.md): HTTPS with a self-signed certificate.

## Observability

- [Metrics HTTP status counters](metrics-http-status-counters/README.md): count responses by HTTP status family.
- [Telemetry](telemetry/README.md): tracing across the greeting and secondary services; use Jaeger to view exported traces.

## Data and messaging

- [Coherence](coherence/README.md): cache-backed credit score service using Coherence CE.
- [Data](data/README.md): Helidon Data with EclipseLink and MySQL; requires a MySQL database (Docker instructions included).
- [Messaging SSE](messaging-sse/README.md): reactive messaging and server-sent events.
