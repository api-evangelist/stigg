# Stigg

Stigg is a pricing and packaging platform providing feature management, entitlements, and usage-based billing for SaaS and API products. It enables engineering teams to integrate once and allows product managers to iterate on pricing without additional engineering effort. Stigg provides advanced metering, entitlement checks, and subscription management via GraphQL and REST APIs with SDKs in multiple languages.

**URL:** [https://raw.githubusercontent.com/api-evangelist/stigg/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/stigg/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- FinOps
- Pricing
- Billing
- Entitlements
- Usage-Based Billing
- SaaS

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-05-02

## APIs

### Stigg GraphQL API

The primary API using GraphQL at api.stigg.io/graphql for customer provisioning, subscription management, entitlement checking, and usage reporting. Authenticated via X-API-KEY header.

**Human URL:** [https://docs.stigg.io/api-and-sdks/integration/backend/graphql](https://docs.stigg.io/api-and-sdks/integration/backend/graphql)

### Stigg REST API (Beta)

Language-agnostic HTTP REST API with SDKs in TypeScript, Python, Go, Ruby, C#, and Java.

**Human URL:** [https://docs.stigg.io/api-and-sdks/integration/overview](https://docs.stigg.io/api-and-sdks/integration/overview)

### SDKs

- **Node.js**: [docs.stigg.io/api-and-sdks/integration/backend/nodejs](https://docs.stigg.io/api-and-sdks/integration/backend/nodejs)
- **Python**: [docs.stigg.io/api-and-sdks/integration/backend/python](https://docs.stigg.io/api-and-sdks/integration/backend/python)
- **Go**: [docs.stigg.io/api-and-sdks/integration/backend/go](https://docs.stigg.io/api-and-sdks/integration/backend/go)
- **React**: [docs.stigg.io/api-and-sdks/integration/frontend/react](https://docs.stigg.io/api-and-sdks/integration/frontend/react)

## OpenAPI Specifications

| Spec | Description |
|---|---|
| [stigg-openapi.yml](openapi/stigg-openapi.yml) | Stigg API — GraphQL endpoint with customer, subscription, and entitlement schemas |

## Capabilities

### Workflow Capabilities

| Capability | Tools | Description |
|---|---|---|
| [pricing-and-entitlements.yaml](capabilities/pricing-and-entitlements.yaml) | 7 | Unified pricing, subscription, and entitlement management workflow |

### Shared Definitions

| Definition | Description |
|---|---|
| [shared/stigg.yaml](capabilities/shared/stigg.yaml) | Stigg GraphQL API consumed definition with 7 operations |

## Rules

| Ruleset | Description |
|---|---|
| [stigg-rules.yml](rules/stigg-rules.yml) | Spectral ruleset enforcing Stigg API conventions |

## JSON Schema

| Schema | Description |
|---|---|
| [stigg-customer-schema.json](json-schema/stigg-customer-schema.json) | Customer entity schema |
| [stigg-entitlement-schema.json](json-schema/stigg-entitlement-schema.json) | Feature entitlement schema with usage limits |

## JSON Structure

| Structure | Description |
|---|---|
| [stigg-entitlement-structure.json](json-structure/stigg-entitlement-structure.json) | Entitlement check response structure |

## JSON-LD

| Context | Description |
|---|---|
| [stigg-context.jsonld](json-ld/stigg-context.jsonld) | JSON-LD context mapping Stigg vocabulary to schema.org |

## Examples

| Example | Description |
|---|---|
| [stigg-provision-customer-example.json](examples/stigg-provision-customer-example.json) | Provision a customer with initial plan enrollment |
| [stigg-check-entitlement-example.json](examples/stigg-check-entitlement-example.json) | Check feature access for a customer |

## Vocabulary

| Vocabulary | Description |
|---|---|
| [stigg-vocabulary.yml](vocabulary/stigg-vocabulary.yml) | Domain vocabulary covering pricing, entitlements, and metering |

## GitHub Organization

- [github.com/stiggio](https://github.com/stiggio) — SDKs (Node.js, Python, Go, Ruby, Java, C#), CLI, Helm charts, and integration examples

## Common Properties

- [Website](https://www.stigg.io/)
- [Documentation](https://docs.stigg.io/)
- [Getting Started](https://docs.stigg.io/getting-started)
- [Sign Up](https://app.stigg.io/)
- [GitHub Organization](https://github.com/stiggio)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
