# Stigg (stigg)

Stigg is a product-led growth monetization platform providing REST and GraphQL APIs for managing pricing plans, entitlements, usage-based billing, feature flags, and subscription lifecycle. It serves as a monetization control layer for SaaS and AI products, enabling engineering teams to implement flexible pricing, granular access control, and real-time usage metering without rebuilding billing infrastructure from scratch. Stigg is SOC 2 Type II and ISO 27001 certified and delivers 99.99% uptime SLA with multi-region deployment.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/stigg/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/stigg/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- FinOps
- Pricing
- Billing
- Entitlements
- Usage-Based Billing
- Feature Flags
- Product-Led Growth
- Subscriptions
- SaaS
- GraphQL
- REST

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-06-13

## APIs

### Stigg GraphQL API

The Stigg GraphQL API provides full access to customer provisioning, subscription management, entitlement checking, usage reporting, and pricing plan management. Authentication uses the X-API-KEY header with a Full access key from the Stigg dashboard. The single endpoint is `https://api.stigg.io/graphql`.

- **Human URL:** [https://docs.stigg.io/api-and-sdks/integration/backend/graphql](https://docs.stigg.io/api-and-sdks/integration/backend/graphql)
- **Base URL:** https://api.stigg.io/graphql

#### Tags

- GraphQL
- Entitlements
- Subscriptions
- Billing

#### Properties

- [Documentation](https://docs.stigg.io/api-and-sdks/integration/backend/graphql)
- [GraphQL Endpoint](https://api.stigg.io/graphql)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/stigg/refs/heads/main/openapi/stigg-openapi.yml)

### Stigg REST API

The Stigg REST API (recommended for new integrations) provides language-agnostic HTTP access to customer management, subscription operations, entitlement checks, and usage reporting. Backed by language-specific SDKs for TypeScript, Python, Go, Ruby, C#, and Java.

- **Human URL:** [https://docs.stigg.io/api-and-sdks/integration/overview](https://docs.stigg.io/api-and-sdks/integration/overview)

#### Tags

- REST
- Entitlements
- Subscriptions
- Billing

#### Properties

- [Documentation](https://docs.stigg.io/api-and-sdks/integration/overview)

### Stigg Node.js SDK

Official Node.js / TypeScript SDK for integrating Stigg entitlements, feature flags, and usage-based billing into backend services.

- **Human URL:** [https://docs.stigg.io/api-and-sdks/integration/backend/nodejs](https://docs.stigg.io/api-and-sdks/integration/backend/nodejs)
- **GitHub:** [https://github.com/stiggio/stigg-typescript](https://github.com/stiggio/stigg-typescript)

### Stigg Python SDK

Official Python SDK for integrating Stigg entitlements and usage-based billing into Python backend services.

- **Human URL:** [https://docs.stigg.io/api-and-sdks/integration/backend/python](https://docs.stigg.io/api-and-sdks/integration/backend/python)
- **GitHub:** [https://github.com/stiggio/stigg-python](https://github.com/stiggio/stigg-python)

### Stigg Go SDK

Official Go SDK for integrating Stigg entitlements and usage-based billing into Go backend services.

- **Human URL:** [https://docs.stigg.io/api-and-sdks/integration/backend/go](https://docs.stigg.io/api-and-sdks/integration/backend/go)
- **GitHub:** [https://github.com/stiggio/stigg-go](https://github.com/stiggio/stigg-go)

### Stigg React SDK

Official React frontend SDK for rendering pricing tables, entitlement gates, and usage meters in React applications.

- **Human URL:** [https://docs.stigg.io/api-and-sdks/integration/frontend/react](https://docs.stigg.io/api-and-sdks/integration/frontend/react)

## Common Properties

- [Website](https://www.stigg.io/)
- [Documentation](https://docs.stigg.io/)
- [Getting Started](https://docs.stigg.io/getting-started)
- [GitHub Organization](https://github.com/stiggio)
- [LinkedIn](https://www.linkedin.com/company/getstigg)
- [Blog](https://www.stigg.io/blog)
- [Pricing](https://www.stigg.io/pricing)
- [Status Page](https://status.stigg.io/)
- [X / Twitter](https://twitter.com/getstigg)
- [Sign Up](https://app.stigg.io/)
- [Integrations](https://www.stigg.io/partners)
- [LLMs.txt](https://docs.stigg.io/llms.txt)
- [Plans](plans/stigg-plans-pricing.yml)
- [Rate Limits](rate-limits/stigg-rate-limits.yml)
- [FinOps](finops/stigg-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
