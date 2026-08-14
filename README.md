# Available .BUILD One-Word Domains (15,278)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-15%2C278%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .build one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **15,278 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 15,278 domains · **Median ask:** $313.73 · **High-demand under $2,500:** 53

**Last updated:** 2026-08-14
**Canonical page:** `https://unique.domains/domains/tld/build`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/build?utm_source=github&utm_medium=referral&utm_campaign=repo_build_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./build.csv">CSV</a> / <a href="./build.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_build_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_build_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .BUILD search](https://unique.domains/domains/tld/build?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_build_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .BUILD search](https://unique.domains/domains/tld/build?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_build_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_build_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .BUILD one-word domain catalog.

### Files

- `build.csv`, public CSV extract (1,000 rows)
- `build.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/build-oneword-domains/main/build.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain        | status    | ask_price | renewal_price | attractiveness | demand | length | registrar     |
| ------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------- |
| nothing.build | premium   | $1,875    | —             | high           | low    | 7      | name.com      |
| acts.build    | available | $39.98    | —             | medium         | low    | 4      | namecheap     |
| glue.build    | resell    | —         | —             | high           | low    | 4      | Go Daddy, LLC |
| abo.build     | premium   | $187.50   | $187.50       | low            | low    | 3      | name.com      |
| arty.build    | available | $32.98    | $39.98        | low            | low    | 4      | namecheap     |
| panda.build   | resell    | —         | —             | high           | medium | 5      | Namecheap     |
| ass.build     | premium   | $3,750    | $3,750        | low            | low    | 3      | name.com      |
| bead.build    | available | $39.98    | —             | high           | low    | 4      | namecheap     |
| glasses.build | resell    | —         | —             | high           | low    | 7      | Dynadot LLC   |
| bae.build     | premium   | $3,750    | —             | high           | low    | 3      | name.com      |
| boer.build    | available | $32.98    | $39.98        | low            | low    | 4      | namecheap     |
| instant.build | resell    | —         | —             | high           | low    | 7      | Porkbun, LLC  |
| beg.build     | premium   | $187.50   | —             | medium         | low    | 3      | name.com      |
| cone.build    | available | $39.98    | —             | medium         | low    | 4      | namecheap     |
| bit.build     | premium   | $1,875    | —             | high           | medium | 3      | name.com      |
| cons.build    | available | $39.98    | —             | high           | low    | 4      | namecheap     |
| bra.build     | premium   | $187.50   | —             | medium         | low    | 3      | name.com      |
| cure.build    | available | $39.98    | —             | high           | low    | 4      | namecheap     |
| con.build     | premium   | $187.50   | —             | high           | low    | 3      | name.com      |
| cyan.build    | available | $39.98    | —             | high           | low    | 4      | namecheap     |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 15,278 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 53 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/build?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_build_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/build?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_build_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_build_oneword_domains&utm_content=related_pricing)

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

This set includes one-word domain names on the .build extension, spanning names like watches.build, criteria.build, and finals.build. Most of the 12,170 domains sit under $500, with a median ask near $395, while a smaller premium tier extends into the low thousands. Demand skews low across the set, though a handful of names — including watch.build, show.build, and fitness.build — show notably higher demand relative to their asking price. Comparing status, price tier, and demand side by side helps separate ownable-now bargains from names that carry premium pricing without matching demand.

- 9,310 available, 2,840 premium-status .build domains
- Median ask $395; most names priced under $500
- 16 names rank in the top 15% for demand
- Undervalued picks: watch.build, show.build, fitness.build

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .BUILD One-Word Domains*. Version 2026-08-14. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .BUILD page](https://unique.domains/domains/tld/build?utm_source=github&utm_medium=referral&utm_campaign=repo_build_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_build_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_build_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_build_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
