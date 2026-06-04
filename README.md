# Available .ROCKS One-Word Domains (10,488)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-10%2C488%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .rocks one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **10,488 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 10,488 domains · **Median ask:** $19.96 · **High-demand under $2,500:** 0

**Last updated:** 2026-06-04  
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

- `rocks.csv` — public CSV extract (1,000 rows)
- `rocks.json` — public JSON extract (1,000 rows)
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

| domain        | status    | ask_price | renewal_price | attractiveness | demand | length | registrar           |
| ------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------------- |
| circle.rocks  | available | $12.99    | —             | 68             | 45     | 6      | name.com            |
| jenny.rocks   | resell    | $12.99    | —             | 87             | 23     | 5      | Dynadot Inc         |
| new.rocks     | premium   | $78.54    | $78.54        | 82             | 48     | 3      | namesilo            |
| stark.rocks   | available | $12.99    | —             | 82             | 44     | 5      | name.com            |
| brain.rocks   | resell    | —         | —             | 70             | 48     | 5      | Spaceship, Inc.     |
| NYC.rocks     | premium   | $854      | $854          | 82             | 42     | 3      | namesilo            |
| rainbow.rocks | available | $12.99    | —             | 82             | 42     | 7      | name.com            |
| sports.rocks  | resell    | —         | —             | 110            | 47     | 6      | Sav.com, LLC - 47   |
| action.rocks  | premium   | $35.40    | $35.40        | 128            | 40     | 6      | namesilo            |
| duke.rocks    | available | $12.99    | —             | 88             | 39     | 4      | name.com            |
| water.rocks   | resell    | —         | —             | 108            | 44     | 5      | united-domains GmbH |
| pool.rocks    | premium   | $242      | $242          | 66             | 39     | 4      | namesilo            |
| public.rocks  | available | $12.99    | —             | 100            | 38     | 6      | name.com            |
| will.rocks    | resell    | —         | —             | 90             | 42     | 4      | Tucows Domains Inc. |
| berlin.rocks  | premium   | $854      | $854          | 78             | 34     | 6      | namesilo            |
| fair.rocks    | available | $12.99    | —             | 82             | 38     | 4      | name.com            |
| Flowers.rocks | resell    | —         | —             | 74             | 40     | 7      | GoDaddy.com, LLC    |
| massage.rocks | premium   | $37.50    | —             | 94             | 32     | 7      | name.com            |
| total.rocks   | available | $12.99    | —             | 108            | 37     | 5      | name.com            |
| angel.rocks   | resell    | —         | —             | 98             | 39     | 5      | Dynadot Inc         |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 10,488 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

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

This selection is entirely made up of .rocks domains. The set includes short dictionary-style words such as smooth.rocks, kind.rocks, born.rocks, and photo.rocks, alongside longer or more specific names like preventive.rocks and midFebruary.rocks. When comparing these domains, focus first on word quality and fit with the .rocks ending. Stronger options are usually easy to read, easy to say, and naturally reinforced by the extension. Weaker options are often longer, seasonal, harder to interpret, or too narrow. Price discipline matters here because the median ask is 16.9, so clarity and memorability should justify any higher ask you consider.

- Short words often read cleaner with .rocks
- Long or seasonal names can be harder to reuse
- Median ask is 16.9 across this selection
- Check wording for trademark or ambiguity risk

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .ROCKS One-Word Domains*. Version 2026-06-04. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .ROCKS page](https://unique.domains/domains/tld/rocks?utm_source=github&utm_medium=referral&utm_campaign=repo_rocks_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_rocks_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_rocks_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_rocks_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
