# Available .ROCKS One-Word Domains (10,489)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-10%2C489%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .rocks one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **10,489 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 10,489 domains · **Median ask:** $19.91 · **High-demand under $2,500:** 0

**Last updated:** 2026-07-07
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

- `rocks.csv`, public CSV extract (1,000 rows)
- `rocks.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/rocks-oneword-domains/main/rocks.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                                 |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------------------------- |
| content.rocks   | resell    | —         | —             | high           | low    | 7      | Dynadot Inc                                               |
| come.rocks      | available | $12.99    | —             | high           | low    | 4      | name.com                                                  |
| action.rocks    | premium   | $35.40    | $35.40        | high           | medium | 6      | namesilo                                                  |
| wholesale.rocks | resell    | —         | —             | high           | low    | 9      | Dynadot Inc                                               |
| there.rocks     | available | $12.99    | —             | high           | low    | 5      | name.com                                                  |
| express.rocks   | resell    | —         | —             | high           | low    | 7      | Global Domains International, Inc. DBA DomainCostClub.com |
| dip.rocks       | available | $12.99    | $27.99        | high           | low    | 3      | name.com                                                  |
| jenny.rocks     | resell    | $12.99    | —             | high           | low    | 5      | Dynadot Inc                                               |
| fat.rocks       | premium   | $78.54    | $78.54        | medium         | low    | 3      | namesilo                                                  |
| due.rocks       | available | $12.99    | —             | high           | low    | 3      | name.com                                                  |
| let.rocks       | resell    | —         | —             | high           | low    | 3      | NameCheap, Inc.                                           |
| new.rocks       | premium   | $78.54    | $78.54        | high           | medium | 3      | namesilo                                                  |
| Eid.rocks       | available | $12.99    | —             | high           | low    | 3      | name.com                                                  |
| band.rocks      | resell    | —         | —             | medium         | low    | 4      | Sav.com, LLC - 22                                         |
| NYC.rocks       | premium   | $854      | $854          | high           | medium | 3      | namesilo                                                  |
| ill.rocks       | available | $12.99    | —             | medium         | low    | 3      | name.com                                                  |
| geek.rocks      | resell    | —         | —             | high           | low    | 4      | Porkbun LLC                                               |
| ser.rocks       | premium   | $123.75   | —             | high           | low    | 3      | name.com                                                  |
| MMR.rocks       | available | $12.99    | —             | high           | low    | 3      | name.com                                                  |
| have.rocks      | resell    | —         | —             | high           | low    | 4      | Sav.com, LLC                                              |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 10,489 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/rocks?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_rocks_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/rocks?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_rocks_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_rocks_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This list includes one-word .rocks domain names such as just.rocks, damn.rocks, content.rocks, and hello.rocks. The .rocks extension pairs short, punchy words with an energetic tone, making these names easy to remember and quick to pronounce. Across this selection of 10,489 domains, the median ask sits near $20, keeping entry costs low. When comparing these domains, founders can look for a name that mirrors their brand voice, while investors can weigh cost against renewal and general demand for the .rocks extension.

- 10,489 one-word .rocks domain names in this set
- Median ask near $20 across the selection
- Short, punchy names like hello.rocks and time.rocks
- Low-cost entry point for testing a brandable .rocks name

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .ROCKS One-Word Domains*. Version 2026-07-07. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .ROCKS page](https://unique.domains/domains/tld/rocks?utm_source=github&utm_medium=referral&utm_campaign=repo_rocks_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_rocks_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_rocks_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_rocks_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
