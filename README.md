# Pomelo (pomelo.la)

Pomelo (pomelo.la) is a Latin American card-issuing and embedded-finance platform. Its REST API lets fintechs and enterprises onboard users (KYC/KYB), issue physical and virtual cards, manage card accounts and balances, process and query transactions, move money with transfers and settlements, and authorize transactions in real time over a synchronous authorization webhook.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/pomelo/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/pomelo/refs/heads/main/apis.yml)

> Disambiguation: This catalog covers **Pomelo at pomelo.la** (the LatAm card issuer / processor, based in Argentina, `api.pomelo.la`). It is not Pomelo the US cross-border remittance and credit-builder app (pomelo.com), nor Pomelo Pay (pomelopay / pomelogroup.com) in the UK.

## Tags

- Fintech
- Card Issuing
- Embedded Finance
- Payments
- Latin America

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Pomelo Users & KYC API

Register and manage end users (cardholders) and the identity verification lifecycle - create, retrieve, search, and modify users, plus KYC and KYB sessions for individuals and companies across operating countries.

- **Human URL:** [https://developers.pomelo.la/en/api-reference/general/users](https://developers.pomelo.la/en/api-reference/general/users)
- **Base URL:** `https://api.pomelo.la`

#### Tags

- Users
- KYC
- KYB
- Identity
- Onboarding

#### Properties

- [Documentation](https://developers.pomelo.la/guides)
- [API Reference](https://developers.pomelo.la/en/api-reference/general/users)
- [OpenAPI](openapi/pomelo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pomelo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pomelo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Pomelo Cards API

Create nominated and innominated physical or virtual cards, retrieve and update card status, affinity group and PIN, activate physical cards, manage batches of innominated cards, and update card shipment addresses.

- **Human URL:** [https://developers.pomelo.la/en/api-reference/cards/issuing/cards](https://developers.pomelo.la/en/api-reference/cards/issuing/cards)
- **Base URL:** `https://api.pomelo.la`

#### Tags

- Cards
- Issuing
- Physical
- Virtual
- Activation

#### Properties

- [Documentation](https://developers.pomelo.la/guides/solutions/issuing/cards)
- [API Reference](https://developers.pomelo.la/en/api-reference/cards/issuing/cards)
- [OpenAPI](openapi/pomelo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pomelo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pomelo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Pomelo Card Accounts API

Manage prepaid/banking card accounts and their balances - query account balances, activities, and movements that back the cards a program issues.

- **Human URL:** [https://developers.pomelo.la/en/api-reference](https://developers.pomelo.la/en/api-reference)
- **Base URL:** `https://api.pomelo.la`

#### Tags

- Card Accounts
- Balance
- Banking
- Movements

#### Properties

- [Documentation](https://developers.pomelo.la/guides)
- [API Reference](https://developers.pomelo.la/en/api-reference)
- [OpenAPI](openapi/pomelo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pomelo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pomelo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Pomelo Transactions API

Search and retrieve processed card transactions and summaries, including purchases, refunds, reversals, and adjustments, with merchant, amount, status, and entry-mode detail.

- **Human URL:** [https://developers.pomelo.la/en/api-reference/cards/processing/transactions](https://developers.pomelo.la/en/api-reference/cards/processing/transactions)
- **Base URL:** `https://api.pomelo.la`

#### Tags

- Transactions
- Processing
- Settlement
- History

#### Properties

- [Documentation](https://developers.pomelo.la/guides/solutions/processing/transactions)
- [API Reference](https://developers.pomelo.la/en/api-reference/cards/processing/transactions)
- [OpenAPI](openapi/pomelo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pomelo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pomelo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Pomelo Authorizations API

Real-time authorizer - Pomelo POSTs each incoming card authorization to the client's signed endpoint, which approves or rejects the transaction within the network time window using a signed response.

- **Human URL:** [https://developers.pomelo.la/en/api-reference/cards/processing/transactions](https://developers.pomelo.la/en/api-reference/cards/processing/transactions)
- **Base URL:** `https://api.pomelo.la`

#### Tags

- Authorizations
- Authorizer
- Real Time
- Webhook

#### Properties

- [Documentation](https://developers.pomelo.la/guides/developers/webhooks)
- [API Reference](https://developers.pomelo.la/en/api-reference)
- [OpenAPI](openapi/pomelo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pomelo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pomelo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Pomelo Transfers API

Move funds across card accounts and settle program balances - create and query transfers and settlements that fund and reconcile the issuing program.

- **Human URL:** [https://developers.pomelo.la/en/api-reference](https://developers.pomelo.la/en/api-reference)
- **Base URL:** `https://api.pomelo.la`

#### Tags

- Transfers
- Money Movement
- Settlements
- Funding

#### Properties

- [Documentation](https://developers.pomelo.la/guides)
- [API Reference](https://developers.pomelo.la/en/api-reference)
- [OpenAPI](openapi/pomelo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pomelo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pomelo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Pomelo Webhooks API

Configure HTTPS endpoints that receive signed event notifications for cards, users, transactions, and adjustments, validated with the x-endpoint, x-signature, and timestamp headers.

- **Human URL:** [https://developers.pomelo.la/guides/developers/webhooks](https://developers.pomelo.la/guides/developers/webhooks)
- **Base URL:** `https://api.pomelo.la`

#### Tags

- Webhooks
- Events
- Notifications
- Signatures

#### Properties

- [Documentation](https://developers.pomelo.la/guides/developers/webhooks)
- [API Reference](https://developers.pomelo.la/en/api-reference)
- [OpenAPI](openapi/pomelo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pomelo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pomelo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/pomelo-la)
- [LinkedIn](https://www.linkedin.com/company/pomelo-la)
- [Website](https://www.pomelo.la)
- [Documentation](https://developers.pomelo.la)
- [Plans](plans/pomelo-plans-pricing.yml)
- [Rate Limits](rate-limits/pomelo-rate-limits.yml)
- [Fin Ops](finops/pomelo-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
