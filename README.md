# Available .ROCKS One-Word Domains (7,725)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-7%2C724%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-7%2C725%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .rocks one-word domains from Unique Domains.

> **Important:** this repository is a **public 7,724-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **7,725 domains** on the canonical page below.

**Public extract:** 7,724 rows · **Live catalog:** 7,725 domains

**Last updated:** 2026-04-13  
**Canonical page:** `https://unique.domains/domains/tld/rocks`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/rocks?utm_source=github&utm_medium=referral&utm_campaign=repo_rocks_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./rocks.csv">CSV</a> / <a href="./rocks.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_rocks_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_rocks_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .ROCKS search](https://unique.domains/domains/tld/rocks?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_rocks_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .ROCKS search](https://unique.domains/domains/tld/rocks?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_rocks_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_rocks_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .ROCKS one-word domain catalog.

### Files

- `rocks.csv` — public CSV extract (7,724 rows)
- `rocks.json` — public JSON extract (7,724 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/rocks-oneword-domains/main/rocks.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                                 |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------------------------- |
| everything.rocks | available | $12.99    | —             | 68             | 47     | 10     | name.com                                                  |
| gas.rocks        | resell    | —         | —             | 72             | 99     | 3      | Network Solutions, LLC                                    |
| law.rocks        | premium   | $85.80    | $85.80        | 82             | 46     | 3      | namecheap                                                 |
| snap.rocks       | available | $12.99    | $27.99        | 90             | 46     | 4      | name.com                                                  |
| adobe.rocks      | resell    | —         | —             | 72             | 70     | 5      | Wild West Domains, LLC                                    |
| pop.rocks        | premium   | $1,000    | $1,000        | 82             | 44     | 3      | name.com                                                  |
| orca.rocks       | available | $12.99    | —             | 76             | 45     | 4      | name.com                                                  |
| open.rocks       | resell    | —         | —             | 106            | 60     | 4      | Porkbun LLC                                               |
| stock.rocks      | premium   | $39       | $39           | 68             | 40     | 5      | namecheap                                                 |
| creator.rocks    | available | $12.99    | $27.99        | 70             | 45     | 7      | name.com                                                  |
| pay.rocks        | resell    | —         | —             | 84             | 60     | 3      | Porkbun LLC                                               |
| about.rocks      | premium   | $1,000    | $1,000        | 94             | 37     | 5      | name.com                                                  |
| evolve.rocks     | available | $12.99    | —             | 84             | 40     | 6      | name.com                                                  |
| flow.rocks       | resell    | —         | —             | 96             | 59     | 4      | Sav.com, LLC                                              |
| cute.rocks       | premium   | $123.75   | $123.75       | 82             | 32     | 4      | name.com                                                  |
| investor.rocks   | available | $12.99    | —             | 82             | 40     | 8      | name.com                                                  |
| jesus.rocks      | resell    | —         | —             | 126            | 52     | 5      | Spaceship, Inc.                                           |
| coral.rocks      | premium   | $123.75   | $123.75       | 68             | 32     | 5      | name.com                                                  |
| scan.rocks       | available | $12.99    | —             | 72             | 39     | 4      | name.com                                                  |
| fast.rocks       | resell    | —         | —             | 82             | 52     | 4      | Global Domains International, Inc. DBA DomainCostClub.com |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 7,724-row public sample | 7,725 live domains                               |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/rocks?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_rocks_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/rocks?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_rocks_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_rocks_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- Unique Domains contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .ROCKS One-Word Domains*. Version 2026-04-13. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .ROCKS page](https://unique.domains/domains/tld/rocks?utm_source=github&utm_medium=referral&utm_campaign=repo_rocks_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_rocks_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_rocks_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_rocks_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
