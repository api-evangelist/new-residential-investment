# new-residential-investment

Profile for **New Residential Investment Corp** in the API Evangelist network. Fortune 1000 (rank 861, prior to rebrand).

> **Rebrand notice:** New Residential Investment Corp (NYSE: NRZ) **rebranded as Rithm Capital Corp (NYSE: RITM) on August 1, 2022**. All current corporate disclosures, investor materials, and operating-business activity are reported under Rithm Capital. This repo retains the legacy `new-residential-investment` identity for continuity with the API Evangelist network registry.

## Company

| Field | Value |
|---|---|
| Legal name | Rithm Capital Corp |
| Former name | New Residential Investment Corp |
| Ticker | NYSE: RITM (formerly NRZ) |
| Headquarters | 799 Broadway, New York, NY |
| Chairman & CEO | Michael Nierenberg |
| Founded | 2013 (spun out of Newcastle Investment Corp / Fortress) |
| Rebrand date | August 1, 2022 |
| Employees (2024) | ~6,045 |
| AUM (2024) | ~$46.05 billion |
| Revenue (2024) | ~$5.206 billion |
| Website | <https://www.rithmcap.com> |

## Operating businesses

Rithm Capital is now a diversified global asset manager rather than a pure mortgage REIT. Its principal operating businesses:

| Business | Role | Acquired |
|---|---|---|
| [Newrez](https://www.newrez.com) | Residential mortgage origination & servicing (~$878B servicing UPB) | 2018 (Shellpoint); Caliber Home Loans April 2021 ($1.675B) |
| [Genesis Capital](https://www.genesiscapital.com) | Business-purpose lender to residential real-estate developers/investors | October 2021 (from Goldman Sachs) |
| [Sculptor Capital Management](https://www.sculptor.com) | Global alternative asset manager (~$34B AUM); formerly Och-Ziff | November 2023 ($719.8M) |
| [Rithm Property Trust](https://www.rithmpt.com) | Externally-managed REIT (formerly Great Ajax), transitioning to commercial real estate | June 2024 |
| [Adoor](https://www.adoor.com) | Single-family rental platform | — |
| [Crestline Investors](https://www.crestlineinvestors.com) | Institutional alternative investment manager | 2024 (majority stake) |
| [Elecor Properties](https://www.paramount-group.com) | Class-A office REIT (formerly Paramount Group, NYSE:PGRE) | Rebranded under Rithm |
| Marcus Loans portfolio | $1.4B consumer-loan portfolio | July 2023 (from Goldman Sachs) |

## API surface

**0 public APIs.** Rithm Capital and each of its operating businesses serve institutional capital-markets counterparties and mortgage borrowers through traditional B2B channels (loan-level data files, MISMO mortgage-industry data exchanges, servicer-to-investor reporting). There is no:

- Public developer portal
- OpenAPI / AsyncAPI specification
- REST or GraphQL API
- Webhook system
- SDK or CLI
- Public status page
- RSS feed
- Substantive public GitHub presence (the `newrez` org exists with zero public repos; `rithmcap` does not exist)

## Artifacts in this repo

| File | Purpose |
|---|---|
| `apis.yml` | APIs.json 0.20 profile documenting the rebrand, corporate history, operating businesses, and the absence of a public developer surface |
| `README.md` | This file |

No `openapi/`, `asyncapi/`, `json-schema/`, `capabilities/`, `rules/`, `plans/`, `rate-limits/`, or `finops/` artifacts are generated — the provider exposes nothing to back them, and the API Evangelist pipeline does not emit empty placeholders.

## Sources

- Rithm Capital homepage: <https://www.rithmcap.com>
- Wikipedia, _Rithm Capital_
- Wikipedia, _Newrez_
- Wikipedia, _Sculptor Capital Management_
