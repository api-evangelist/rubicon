# Rubicon (rubicon)

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

Rubicon (formerly NYSE: RBT) is a waste, recycling, and sustainability technology company founded in 2008. It went public in 2022 via a SPAC merger with Founder SPAC at a pro forma valuation of roughly $1.7 billion, branding itself a "digital challenger" to the traditional waste-hauling industry with a marketplace connecting waste generators to independent haulers plus the RUBICONSmartCity fleet-and-routing platform used by more than 70 municipalities.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/rubicon/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/rubicon/refs/heads/main/apis.yml)

## Operating Status

Rubicon's public-company era did not go well:

- **2022** - Went public on NYSE (ticker: RBT) via SPAC merger with Founder SPAC, pro forma valuation ~$1.7 billion, ~$196.8M raised.
- **2023** - Layoffs and debt restructuring as the company struggled to reach profitability post-listing.
- **May 2024** - Divested its entire fleet-technology and smart-city business unit - RUBICONSmartCity, RUBICONPro, and RUBICONPremier - to Rodina Capital (controlled by board member Andres Chico) for ~$68 million plus a possible $12 million earnout. Those assets subsequently landed with Routeware.
- **June 2024** - Received a delisting notice and was suspended from NYSE trading.
- **Early 2025** - Deregistered its securities with the SEC and ceased public financial reporting, becoming a privately held company. Jose Miguel Enrich, via MBI Holdings, holds a majority stake (~51-59.5%) after converting preferred equity.
- **Ongoing** - Shareholder litigation seeking $330M+ tied to change-of-control terms triggered by the Enrich transaction.

**Rubicon is still operating today**, but as a smaller, privately held company focused on its core enterprise waste-brokerage business rather than the smart-city/fleet-technology ambitions that took it public.

## What Rubicon Does Today

- **RUBICONConnect** - The current flagship platform: service, equipment, pickup, and cost visibility for enterprise waste generators (customers cited include Chipotle and FedEx), plus sustainability reporting via app and desktop portal.
- **RUBICONRegWatch** - Regulatory compliance tracking.
- **Technical Advisory Services** - Circular-economy and sustainability strategy consulting.
- **Rubicon Now** - On-demand dumpster rental, currently in Atlanta, Fort Worth, and Houston.
- **Mail-Back Recycling** - Consumer recycling-by-mail program.
- **RUBICONPro / hauler technologies** - Fleet performance dashboards, in-cab interface, and telematics pod are still marketed on rubicon.com's hauler pages, even though the underlying smart-city/fleet-technology business was sold to Rodina Capital / Routeware in May 2024 - the site content appears not fully reconciled with the divestiture.

## Developer / API Status: Gated, No Public Documentation

This entry is an **honest stub**. Research turned up no public developer portal, no public API reference documentation, and no published OpenAPI specification anywhere on rubicon.com.

The one discoverable API artifact tied to the rubicon.com domain is a Swagger UI titled **"Routeware Smartcity Public Api"** at a dev subdomain:

- `https://haulerpublic-api.dev.aws.rubicon.com/swagger/index.html`

This is almost certainly leftover infrastructure from the divested fleet-technology/smart-city business (now Routeware's), still resolving under a `rubicon.com` subdomain. It returned **HTTP 503 Service Unavailable** on every check made during this review (both via browser fetch and direct `curl`) and is not publicly reachable or documented for self-serve use.

Any API-level integration Rubicon references publicly - for example, integrating RUBICONSmartCity-era technology with a city's existing 311 system - is described as something "Rubicon will work with cities to execute," i.e. a negotiated, partner-by-partner integration gated behind sales and onboarding, not a self-serve developer program.

No endpoints are modeled in this repository because there is no real or credible surface to model honestly - `apis: []` in `apis.yml` reflects that.

## Pricing

Pricing for RUBICONConnect and Rubicon's other enterprise services is entirely **quote-based and negotiated per contract**. No public pricing page, tiers, or usage limits are published, so no `plans/`, `rate-limits/`, or `finops/` artifacts are included in this repository - creating them would require fabricating numbers that don't exist publicly.

## Tags

- Waste Management
- Recycling
- Sustainability
- Circular Economy
- Fleet Management
- Smart City
- Enterprise
- Gated API

## Timestamps

- **Created:** 2026-07-03
- **Modified:** 2026-07-03

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/rubicon-global)
- [Website](https://www.rubicon.com)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
