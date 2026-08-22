# Pomelo (pomelo.la)

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
