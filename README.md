# Available .PAGE One-Word Domains (11,984)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C984%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .page one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,984 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,984 domains · **Median ask:** $80.59 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
**Canonical page:** `https://unique.domains/domains/tld/page`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/page?utm_source=github&utm_medium=referral&utm_campaign=repo_page_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./page.csv">CSV</a> / <a href="./page.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_page_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_page_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .PAGE search](https://unique.domains/domains/tld/page?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_page_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .PAGE search](https://unique.domains/domains/tld/page?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_page_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_page_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .PAGE one-word domain catalog.

### Files

- `page.csv` — public CSV extract (1,000 rows)
- `page.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/page-oneword-domains/main/page.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| Chanel.page      | available | $16.98    | —             | 80             | 77     | 6      | namecheap |
| Books.page       | premium   | $1,398.60 | $1,398.60     | 52             | 49     | 5      | namecheap |
| RedSox.page      | available | $16.98    | —             | 72             | 60     | 7      | namecheap |
| coins.page       | premium   | $311.25   | —             | 56             | 41     | 5      | name.com  |
| shortcuts.page   | available | $15.99    | —             | 48             | 41     | 10     | name.com  |
| aliens.page      | premium   | $70.21    | $70.21        | 56             | 35     | 6      | namesilo  |
| unicorns.page    | available | $15.99    | —             | 73             | 21     | 8      | name.com  |
| tickets.page     | premium   | $623.75   | —             | 64             | 34     | 7      | name.com  |
| affiliates.page  | available | $12.79    | $12.99        | 60             | 21     | 10     | namesilo  |
| Cats.page        | premium   | $1,398.60 | $1,398.60     | 59             | 33     | 4      | namecheap |
| HarryPotter.page | available | $16.98    | —             | 72             | 20     | 12     | namecheap |
| payments.page    | premium   | $1,248.75 | —             | 58             | 33     | 8      | name.com  |
| smartest.page    | available | $12.79    | $12.99        | 64             | 20     | 8      | namesilo  |
| William.page     | premium   | $348.60   | $348.60       | 74             | 31     | 7      | namecheap |
| happier.page     | available | $15.99    | —             | 62             | 16     | 7      | name.com  |
| letsgo.page      | premium   | $73.75    | —             | 57             | 31     | 7      | name.com  |
| solarpower.page  | available | $15.99    | —             | 84             | 15     | 11     | name.com  |
| solutions.page   | premium   | $623.75   | —             | 56             | 31     | 9      | name.com  |
| sparkles.page    | available | $15.99    | —             | 62             | 15     | 8      | name.com  |
| videos.page      | premium   | $623.75   | —             | 52             | 30     | 6      | name.com  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,984 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/page?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_page_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/page?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_page_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_page_oneword_domains&utm_content=related_pricing)

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

These domains are one-word names on the .page extension. The set includes plain dictionary words, broad categories, and more expressive terms such as boat.page, woman.page, complement.page, manifest.page, artist.page, lecture.page, and yesterday.page. When comparing these domains, focus first on whether the word is strong enough to carry a standalone web identity on a less common extension. Then weigh asking price against how clear, memorable, and commercially usable the word is. For founders, the best picks are easy to say and easy to trust. For investors, the better candidates are words with broad buyer appeal and clean resale logic at a modest entry price.

- Prioritize clear words that stand on their own with .page
- Use price discipline: median ask is 80.59
- Favor broad-use words over narrow or awkward terms
- Check trademark risk on branded or loaded terms

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .PAGE One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .PAGE page](https://unique.domains/domains/tld/page?utm_source=github&utm_medium=referral&utm_campaign=repo_page_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_page_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_page_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_page_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
