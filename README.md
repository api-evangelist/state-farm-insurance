# State Farm Insurance (state-farm-insurance)

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

State Farm Insurance refers to the primary insurance operations of State Farm Mutual Automobile Insurance Company and its affiliated entities, headquartered in Bloomington, Illinois. As the largest property and casualty insurer in the United States, State Farm Insurance provides auto, home, renters, life, health, commercial, and farm insurance products to over 83 million policies across 91 million accounts. The company operates through approximately 19,000 exclusive agents and has a robust digital platform. State Farm Insurance maintains a Partner Gateway developer portal (developer.statefarm.com) offering APIs for embedded insurance, partner integrations, and B2B connectivity. The company has also heavily invested in cloud infrastructure on AWS and has open-sourced numerous DevOps and infrastructure tools via its GitHub organization.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/state-farm-insurance/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/state-farm-insurance/refs/heads/main/apis.yml)

## Timestamps

- **Modified:** 2026-05-19

## APIs

### Renters Insurance API

The State Farm Renters Insurance API allows property management companies, real estate platforms, and partner aggregators to embed renters insurance quoting and policy issuance directly into their workflows. Renters can receive a customized State Farm quote without leaving the partner application. State Farm is the top-ranked renters insurance provider in the United States. The API supports quote requests, coverage selection, policy binding, and policy status retrieval.

- **Human URL:** [https://developer.statefarm.com/api/renters](https://developer.statefarm.com/api/renters)
- **Base URL:** `https://api.statefarm.com/v1`

#### Tags

- Insurance
- Renters Insurance
- Embedded Insurance
- Property
- Partner

#### Properties

- [Documentation](https://developer.statefarm.com/api/renters)
- [OpenAPI](openapi/state-farm-insurance-renters-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/state-farm-insurance-renters.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/state-farm-insurance-renters.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Auto Insurance API

The State Farm Auto Insurance API enables partners in automotive, telematics, and financial services to embed State Farm auto insurance products into their platforms. Use cases include in-dealership insurance quoting at point of sale, connected car insurance integrations, and lender-required coverage verification. State Farm is the largest auto insurer in the US with over 40 million auto policies. The API supports quote generation, coverage retrieval, and policy status inquiries.

- **Human URL:** [https://developer.statefarm.com/](https://developer.statefarm.com/)
- **Base URL:** `https://api.statefarm.com/v1`

#### Tags

- Insurance
- Auto Insurance
- Vehicles
- Telematics
- Partner

#### Properties

- [Documentation](https://developer.statefarm.com/)
- [Postman Collection](collections/state-farm-insurance-renters.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/state-farm-insurance-renters.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Homeowners Insurance API

The State Farm Homeowners Insurance API enables mortgage lenders, real estate platforms, and partner networks to offer homeowners insurance quoting and policy integration. Supports closing day insurance coordination, escrow verification, and coverage inquiry for lenders requiring collateral protection evidence. State Farm is one of the largest homeowners insurance providers in the US.

- **Human URL:** [https://developer.statefarm.com/](https://developer.statefarm.com/)
- **Base URL:** `https://api.statefarm.com/v1`

#### Tags

- Insurance
- Homeowners Insurance
- Mortgage
- Real Estate
- Partner

#### Properties

- [Documentation](https://developer.statefarm.com/)
- [Postman Collection](collections/state-farm-insurance-renters.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/state-farm-insurance-renters.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### B2B Insurance Inquiry API

The State Farm B2B Insurance Inquiry API provides home and auto lenders with a programmatic way to verify that borrowers maintain adequate insurance coverage on financed properties and vehicles. Lenders can query active policy status, coverage amounts, and expiration dates. This supports regulatory compliance requirements for collateral insurance verification and helps lenders reduce force-placed insurance costs.

- **Human URL:** [https://b2b.statefarm.com/b2b-content/home-auto-lenders/ins-inquiry](https://b2b.statefarm.com/b2b-content/home-auto-lenders/ins-inquiry)
- **Base URL:** `https://b2b.statefarm.com/api/v1`

#### Tags

- Insurance
- B2B
- Lenders
- Verification
- Compliance

#### Properties

- [Documentation](https://b2b.statefarm.com/b2b-content/home-auto-lenders/ins-inquiry)
- [Postman Collection](collections/state-farm-insurance-renters.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/state-farm-insurance-renters.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.statefarm.com)
- [Developer  Portal](https://developer.statefarm.com)
- [Git Hub](https://github.com/StateFarmIns)
- [Engineering  Blog](https://engineering.statefarm.com/blog)
- [B2 B  Portal](https://b2b.statefarm.com)
- [LinkedIn](https://www.linkedin.com/company/state-farm)
- [Twitter](https://twitter.com/StateFarm)
- [Newsroom](https://newsroom.statefarm.com)
- [Privacy Policy](https://www.statefarm.com/customer-care/privacy-security/privacy/privacy-policy)
- [Terms of Service](https://www.statefarm.com/customer-care/legal-disclaimer)
- [OpenAPI](openapi/state-farm-insurance-renters-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/state-farm-insurance-renters-policy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/state-farm-insurance-renters-policy-structure.json)
- [JSON-LD](json-ld/state-farm-insurance-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/state-farm-insurance-vocabulary.yml)
- [Spectral Rules](rules/state-farm-insurance-rules.yml)
