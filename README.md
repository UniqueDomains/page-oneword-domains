# Available .PAGE One-Word Domains (16,738)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-16%2C738%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .page one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **16,738 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 16,738 domains · **Median ask:** $68.36 · **High-demand under $2,500:** 7

**Last updated:** 2026-08-19
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

- `page.csv`, public CSV extract (1,000 rows)
- `page.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/page-oneword-domains/main/page.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain     | status    | ask_price | renewal_price | attractiveness | demand | length | registrar         |
| ---------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------- |
| alar.page  | available | $12.79    | $12.99        | low            | low    | 4      | namesilo          |
| forum.page | resell    | —         | —             | high           | low    | 5      | Uniregistrar Corp |
| act.page   | premium   | $1,248.75 | —             | high           | low    | 3      | name.com          |
| arum.page  | available | $12.79    | $12.99        | low            | low    | 4      | namesilo          |
| all.page   | premium   | $623.75   | $623.75       | high           | medium | 3      | name.com          |
| awed.page  | available | $12.79    | $12.99        | low            | low    | 4      | namesilo          |
| are.page   | premium   | $623.75   | —             | high           | low    | 3      | name.com          |
| awry.page  | available | $12.79    | $12.99        | low            | low    | 4      | namesilo          |
| ash.page   | premium   | $311.25   | —             | medium         | low    | 3      | name.com          |
| fist.page  | available | $12.79    | $12.99        | high           | low    | 4      | namesilo          |
| bad.page   | premium   | $623.75   | —             | high           | medium | 3      | name.com          |
| howl.page  | available | $12.79    | $12.99        | high           | low    | 4      | namesilo          |
| bra.page   | premium   | $311.25   | —             | medium         | low    | 3      | name.com          |
| nyse.page  | available | $12.79    | $12.99        | medium         | low    | 4      | namesilo          |
| bug.page   | premium   | $311.25   | —             | high           | low    | 3      | name.com          |
| Sony.page  | available | $12.79    | $12.99        | high           | medium | 4      | namesilo          |
| eat.page   | premium   | $1,248.75 | —             | high           | low    | 3      | name.com          |
| wore.page  | available | $12.79    | $12.99        | low            | low    | 4      | namesilo          |
| ego.page   | premium   | $623.75   | —             | medium         | low    | 3      | name.com          |
| xcvi.page  | available | $12.79    | $12.99        | low            | low    | 4      | namesilo          |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 16,738 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 7 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/page?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_page_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/page?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_page_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_page_oneword_domains&utm_content=related_pricing)

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

This is a focused set of one-word and short-phrase .page domain names, drawn from everyday language rather than invented brand terms. Names like watches.page, superhero.page, and flaxseed.page show the range: single nouns, compound phrases, and playful expressions, all short enough to read and remember at a glance. With a median asking price near $101 across 11,988 listings, the set spans budget-friendly options alongside pricier standouts. When comparing names here, weigh length, spelling simplicity, and how directly the word maps to a topic or product category—qualities that matter whether you're shortlisting a brand name or scanning for pricing outliers.

- 11,988 one-word .page domains in this selection
- Median asking price near $101 across the set
- Short, memorable names—easy to spell and brand
- Mix of everyday nouns, phrases, and coined terms

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .PAGE One-Word Domains*. Version 2026-08-19. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .PAGE page](https://unique.domains/domains/tld/page?utm_source=github&utm_medium=referral&utm_campaign=repo_page_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_page_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_page_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_page_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
