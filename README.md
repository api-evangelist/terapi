# Terapi

Terapi is an open-source embedded integration platform for building native product integrations. It provides a self-hosted iPaaS with pre-built connectors, authentication management, unified APIs, and workflow automation for SaaS products needing to offer native third-party integrations to their customers.

**Type:** company (open source)  
**Website:** [https://terapi.dev](https://terapi.dev)  
**Documentation:** [https://docs.terapi.dev](https://docs.terapi.dev)  
**GitHub:** [https://github.com/terapi-dev](https://github.com/terapi-dev)

## APIs

### Terapi API
Terapi's REST API enables authentication management, connection handling, data synchronization, and action triggering across integrated third-party services. Build native integrations into your SaaS product using Terapi's pre-built connector ecosystem.

- **Documentation:** [https://docs.terapi.dev](https://docs.terapi.dev)
- **OpenAPI:** [openapi/terapi-openapi.yml](openapi/terapi-openapi.yml)

## OpenAPI Specifications

| Spec | Description |
|---|---|
| [terapi-openapi.yml](openapi/terapi-openapi.yml) | Terapi REST API - connections, integrations, sync, actions, auth tokens |

## Spectral Rules

| Ruleset | Description |
|---|---|
| [terapi-rules.yml](rules/terapi-rules.yml) | Spectral rules enforcing Terapi API conventions |

## Naftiko Capabilities

### Shared Definitions
| File | Description |
|---|---|
| [capabilities/shared/terapi.yaml](capabilities/shared/terapi.yaml) | Terapi API consumed definition |

### Workflow Capabilities
| File | Description |
|---|---|
| [capabilities/embedded-integrations.yaml](capabilities/embedded-integrations.yaml) | Full embedded iPaaS workflow (connections, sync, actions, auth) |

## JSON Schemas

| Schema | Description |
|---|---|
| [terapi-connection-schema.json](json-schema/terapi-connection-schema.json) | Integration connection schema |

## JSON Structures

| Structure | Description |
|---|---|
| [terapi-connection-structure.json](json-structure/terapi-connection-structure.json) | Connection field documentation |

## JSON-LD

| Context | Description |
|---|---|
| [terapi-context.jsonld](json-ld/terapi-context.jsonld) | JSON-LD context for integration platform concepts |

## Examples

| Example | Description |
|---|---|
| [terapi-list-connections-example.json](examples/terapi-list-connections-example.json) | List connections request/response |
| [terapi-trigger-action-example.json](examples/terapi-trigger-action-example.json) | Trigger action (create GitHub issue) request/response |

## Vocabulary

| Vocabulary | Description |
|---|---|
| [terapi-vocabulary.yml](vocabulary/terapi-vocabulary.yml) | Embedded iPaaS and integration platform vocabulary |

## Links

- **Website:** [https://terapi.dev](https://terapi.dev)
- **Documentation:** [https://docs.terapi.dev](https://docs.terapi.dev)
- **GitHub:** [https://github.com/terapi-dev](https://github.com/terapi-dev)
