# SOA (Service-Oriented Architecture)

Service-Oriented Architecture (SOA) is an architectural style for building software applications as a collection of loosely coupled, interoperable services. Each service encapsulates a specific business capability and communicates with others through well-defined interfaces — commonly using SOAP, REST, or messaging protocols. SOA enables enterprise integration, reusability, and flexibility across heterogeneous systems.

## Key Concepts

- **Services** — discrete, reusable units of business functionality
- **Service Contract** — formal interface definition (WSDL, OpenAPI)
- **Enterprise Service Bus (ESB)** — middleware for routing, transformation, orchestration
- **Service Registry** — directory for service discovery and governance
- **Loose Coupling** — services interact through stable contracts, not implementations
- **Orchestration & Choreography** — patterns for composing services into business processes

## Standards

- [SOAP 1.2 (W3C)](https://www.w3.org/TR/soap12/)
- [WSDL 2.0 (W3C)](https://www.w3.org/TR/wsdl20/)
- [OASIS SOA Reference Model](https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=soa-rm)
- WS-* (WS-Security, WS-ReliableMessaging, WS-Transaction, WS-Policy)

## Artifacts

| Type | File |
|------|------|
| JSON Schema | [json-schema/soa-service-schema.json](json-schema/soa-service-schema.json) |
| JSON Structure | [json-structure/soa-service-structure.json](json-structure/soa-service-structure.json) |
| JSON-LD Context | [json-ld/soa-context.jsonld](json-ld/soa-context.jsonld) |
| Vocabulary | [vocabulary/soa-vocabulary.yml](vocabulary/soa-vocabulary.yml) |
| Example: Service Registry Entry | [examples/soa-service-registry-example.json](examples/soa-service-registry-example.json) |

## Timestamps

- **Created:** 2025
- **Modified:** 2026-05-02
