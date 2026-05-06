# Available .CRUISES One-Word Domains (12,673)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C673%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .cruises one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,673 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,673 domains · **Median ask:** $22.64 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
**Canonical page:** `https://unique.domains/domains/tld/cruises`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/cruises?utm_source=github&utm_medium=referral&utm_campaign=repo_cruises_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./cruises.csv">CSV</a> / <a href="./cruises.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_cruises_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cruises_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .CRUISES search](https://unique.domains/domains/tld/cruises?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_cruises_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .CRUISES search](https://unique.domains/domains/tld/cruises?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_cruises_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cruises_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .CRUISES one-word domain catalog.

### Files

- `cruises.csv` — public CSV extract (1,000 rows)
- `cruises.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/cruises-oneword-domains/main/cruises.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain            | status    | ask_price | renewal_price | attractiveness | demand | length | registrar      |
| ----------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | -------------- |
| homes.cruises     | available | $14.99    | —             | 86             | 34     | 5      | name.com       |
| finals.cruises    | available | $14.99    | —             | 80             | 7      | 6      | name.com       |
| jewels.cruises    | available | $14.99    | —             | 80             | 15     | 6      | name.com       |
| barup.cruises     | available | $14.99    | —             | 82             | 2      | 6      | name.com       |
| Apples.cruises    | available | $68.98    | —             | 90             | 16     | 6      | namecheap      |
| edamame.cruises   | available | $14.99    | —             | 80             | 9      | 7      | name.com       |
| toneup.cruises    | available | $14.99    | —             | 80             | 5      | 7      | name.com       |
| pierogi.cruises   | available | $14.99    | —             | 82             | 7      | 7      | name.com       |
| robots.cruises    | available | $14.99    | —             | 62             | 47     | 6      | name.com       |
| flights.cruises   | resell    | —         | —             | 61             | 22     | 7      | Name.com, Inc. |
| etc.cruises       | premium   | $82.50    | —             | 58             | 34     | 3      | name.com       |
| skills.cruises    | available | $14.99    | —             | 58             | 47     | 6      | name.com       |
| systems.cruises   | premium   | $123.75   | —             | 46             | 27     | 7      | name.com       |
| Tools.cruises     | available | $68.98    | —             | 56             | 40     | 5      | namecheap      |
| seas.cruises      | premium   | $123.75   | —             | 58             | 13     | 4      | name.com       |
| stories.cruises   | available | $14.99    | —             | 58             | 36     | 7      | name.com       |
| LongBeach.cruises | premium   | $138.60   | $138.60       | 62             | 11     | 10     | namecheap      |
| aliens.cruises    | available | $14.99    | —             | 56             | 35     | 6      | name.com       |
| spectra.cruises   | available | $14.99    | —             | 62             | 34     | 7      | name.com       |
| payments.cruises  | available | $14.99    | —             | 58             | 33     | 8      | name.com       |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,673 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/cruises?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_cruises_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/cruises?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_cruises_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_cruises_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of one-word domains on the .cruises extension. The set spans broad dictionary-style terms and more niche words, with examples such as girls.cruises, jewels.cruises, homes.cruises, and forces.cruises. For founders, the main question is whether the word feels directly relevant to cruise travel or can still support a credible brand. For investors, the key test is tighter: whether the word has clear category fit, commercial meaning, and a low enough ask to justify the extension-specific demand profile. With a median ask of 22.64, price discipline matters less than word quality and relevance.

- All names use the .cruises extension
- 12,673 one-word domains in this selection
- Median ask across the set is 22.64
- Favor clear, travel-relevant words over vague terms

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .CRUISES One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .CRUISES page](https://unique.domains/domains/tld/cruises?utm_source=github&utm_medium=referral&utm_campaign=repo_cruises_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_cruises_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_cruises_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cruises_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
