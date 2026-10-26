# WEC Energy Group

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

WEC Energy Group (NYSE: WEC) is one of the nation's premier energy companies, serving 4.4 million customers across Wisconsin, Illinois, Michigan, and Minnesota with electricity and natural gas service. The company operates through regional utilities including We Energies, Wisconsin Public Service, Peoples Gas, North Shore Gas, Minnesota Energy Resources, Michigan Gas Utilities, and Upper Michigan Energy Resources.

**Type:** Company (Fortune 500)
**NYSE:** WEC
**Website:** [wecenergygroup.com](https://www.wecenergygroup.com)
**Headquarters:** Milwaukee, Wisconsin

## Subsidiaries

| Subsidiary | States | Services |
|-----------|--------|----------|
| We Energies | Wisconsin | Electric + Natural Gas |
| Wisconsin Public Service | Wisconsin | Electric + Natural Gas |
| Peoples Gas | Illinois (Chicago) | Natural Gas |
| North Shore Gas | Illinois | Natural Gas |
| Minnesota Energy Resources | Minnesota | Natural Gas |
| Michigan Gas Utilities | Michigan | Natural Gas |
| Upper Michigan Energy Resources | Michigan | Electric + Natural Gas |
| Bluewater Gas Storage | Michigan | Natural Gas Storage |

## APIs

| API | Description |
|-----|-------------|
| [Customer Portal API](https://www.we-energies.com/) | Account management, bill payment, usage history, outage reporting |
| [Green Button Energy Usage Data](https://www.energy.gov/data/green-button) | ESPI-standard customer energy data access |
| [We Energies Outage Map](https://www.we-energies.com/outages-safety/outages/outage-map/) | Real-time electricity outage information |
| [Peoples Gas Customer Service](https://www.peoplesgas.com/) | Account and billing for Chicago natural gas customers |
| [Investor Relations](https://www.wecenergygroup.com/investor-relations/) | SEC filings, earnings, dividend, and stock information |

## Artifacts

### JSON Schemas
- [wec-energy-usage-schema.json](json-schema/wec-energy-usage-schema.json) — Energy usage data records (Green Button / ESPI aligned)
- [wec-energy-account-schema.json](json-schema/wec-energy-account-schema.json) — Customer account schema
- [wec-energy-outage-schema.json](json-schema/wec-energy-outage-schema.json) — Outage event schema

### JSON Structures
- [wec-energy-account-structure.json](json-structure/wec-energy-account-structure.json) — Account field documentation

### JSON-LD Contexts
- [wec-energy-context.jsonld](json-ld/wec-energy-context.jsonld) — Linked data context for WEC Energy resources

### Examples
- [wec-energy-usage-example.json](examples/wec-energy-usage-example.json) — Monthly energy usage data example

### Vocabulary
- [wec-energy-vocabulary.yml](vocabulary/wec-energy-vocabulary.yml) — WEC Energy Group terminology

## Customer Programs

- **Green Button Connect My Data** — Authorize apps to access your energy usage data
- **Focus on Energy** — Wisconsin statewide energy efficiency program
- **Budget Billing** — Levelized monthly payments
- **Paperless Billing / eBill** — Electronic bill delivery
- **AutoPay** — Automatic bill payment
- **Outage Alerts** — SMS and email notifications

## Common Properties

- [Website](https://www.wecenergygroup.com)
- [Customer Portal](https://www.we-energies.com/)
- [Peoples Gas Portal](https://www.peoplesgas.com/)
- [Wisconsin Public Service Portal](https://www.wisconsinpublicservice.com/)
- [Investor Relations](https://www.wecenergygroup.com/investor-relations/)
- [Sustainability](https://www.wecenergygroup.com/sustainability/)
- [Careers](https://careers.wecenergygroup.com/)
- [LinkedIn](https://www.linkedin.com/company/wec-energy-group)
- [Twitter](https://twitter.com/WECEnergyGroup)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
