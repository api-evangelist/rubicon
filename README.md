# Rubicon (rubicon)

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
