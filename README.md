# Available .CRUISES One-Word Domains (17,621)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-17%2C621%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .cruises one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **17,621 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 17,621 domains · **Median ask:** $19.37 · **High-demand under $2,500:** 3

**Last updated:** 2026-08-20
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

- `cruises.csv`, public CSV extract (1,000 rows)
- `cruises.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/cruises-oneword-domains/main/cruises.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar         |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------- |
| atp.cruises     | available | $14.99    | —             | medium         | low    | 3      | name.com          |
| boat.cruises    | resell    | —         | —             | high           | low    | 4      | Porkbun LLC       |
| bit.cruises     | premium   | $118.80   | $118.80       | high           | medium | 3      | namesilo          |
| awe.cruises     | available | $14.99    | —             | high           | low    | 3      | name.com          |
| lake.cruises    | resell    | —         | —             | high           | low    | 4      | GoDaddy.com, LLC  |
| day.cruises     | premium   | $500      | —             | high           | low    | 3      | name.com          |
| clv.cruises     | available | $14.99    | $81.99        | low            | low    | 3      | name.com          |
| forum.cruises   | resell    | —         | —             | high           | low    | 5      | Porkbun LLC       |
| fee.cruises     | premium   | $118.80   | $118.80       | high           | low    | 3      | namesilo          |
| DJI.cruises     | available | $14.99    | —             | high           | low    | 3      | name.com          |
| domain.cruises  | resell    | —         | —             | high           | medium | 6      | Automattic Inc.   |
| His.cruises     | premium   | $118.80   | $118.80       | high           | low    | 3      | namesilo          |
| Eid.cruises     | available | $14.99    | —             | high           | low    | 3      | name.com          |
| premium.cruises | resell    | —         | —             | high           | low    | 7      | Sav.com, LLC - 12 |
| hub.cruises     | premium   | $242      | $242          | high           | medium | 3      | namesilo          |
| era.cruises     | available | $14.99    | —             | high           | medium | 3      | name.com          |
| inc.cruises     | premium   | $118.80   | $118.80       | medium         | low    | 3      | namesilo          |
| gas.cruises     | available | $14.99    | —             | high           | low    | 3      | name.com          |
| net.cruises     | premium   | $500      | —             | high           | medium | 3      | name.com          |
| ivy.cruises     | available | $14.99    | —             | high           | low    | 3      | name.com          |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 17,621 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 3 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/cruises?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_cruises_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/cruises?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_cruises_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_cruises_oneword_domains&utm_content=related_pricing)

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

This list covers 12,672 one-word .cruises domains, drawn from a wide range of styles including compound travel terms, lifestyle words, and descriptive nouns. With a median asking price near $21.54, most names in this set remain affordable for early acquisition. Whether the goal is securing a memorable brand name or building a small portfolio in the travel space, these domains offer a low-cost entry point into a niche, industry-specific TLD.

- 12,672 one-word .cruises domains across varied styles
- Median asking price near $21.54, low entry cost
- Names span travel, hospitality, and lifestyle themes
- Ownable now for founders building cruise-related brands

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .CRUISES One-Word Domains*. Version 2026-08-20. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .CRUISES page](https://unique.domains/domains/tld/cruises?utm_source=github&utm_medium=referral&utm_campaign=repo_cruises_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_cruises_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_cruises_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cruises_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
