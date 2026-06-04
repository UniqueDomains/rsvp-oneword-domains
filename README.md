# Available .RSVP One-Word Domains (12,792)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C792%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .rsvp one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,792 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,792 domains · **Median ask:** $107.16 · **High-demand under $2,500:** 0

**Last updated:** 2026-06-04  
**Canonical page:** `https://unique.domains/domains/tld/rsvp`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/rsvp?utm_source=github&utm_medium=referral&utm_campaign=repo_rsvp_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./rsvp.csv">CSV</a> / <a href="./rsvp.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_rsvp_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_rsvp_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .RSVP search](https://unique.domains/domains/tld/rsvp?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_rsvp_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .RSVP search](https://unique.domains/domains/tld/rsvp?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_rsvp_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_rsvp_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .RSVP one-word domain catalog.

### Files

- `rsvp.csv` — public CSV extract (1,000 rows)
- `rsvp.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/rsvp-oneword-domains/main/rsvp.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| nationwide.rsvp | available | $14.99    | $19.99        | 76             | 66     | 10     | name.com  |
| mint.rsvp       | premium   | $311.25   | —             | 72             | 79     | 4      | name.com  |
| priceless.rsvp  | available | $14.99    | —             | 75             | 66     | 9      | name.com  |
| prompt.rsvp     | premium   | $73.75    | —             | 114            | 69     | 6      | name.com  |
| Nutella.rsvp    | available | $14.99    | —             | 72             | 66     | 7      | name.com  |
| now.rsvp        | premium   | $623.75   | —             | 78             | 67     | 3      | name.com  |
| tylenol.rsvp    | available | $14.99    | —             | 78             | 60     | 7      | name.com  |
| aladdin.rsvp    | premium   | $73.75    | —             | 76             | 67     | 7      | name.com  |
| WhiteSox.rsvp   | available | $14.99    | —             | 66             | 60     | 9      | name.com  |
| pay.rsvp        | premium   | $1,248.75 | —             | 84             | 63     | 3      | name.com  |
| autonomous.rsvp | available | $14.99    | —             | 76             | 44     | 10     | name.com  |
| Your.rsvp       | premium   | $623.75   | —             | 68             | 59     | 4      | name.com  |
| fucking.rsvp    | available | $14.99    | —             | 58             | 43     | 7      | name.com  |
| music.rsvp      | premium   | $1,248.75 | —             | 84             | 53     | 5      | name.com  |
| sovereign.rsvp  | available | $14.99    | —             | 86             | 41     | 9      | name.com  |
| business.rsvp   | premium   | $1,298.70 | $1,298.70     | 100            | 52     | 8      | namecheap |
| visualize.rsvp  | available | $14.99    | —             | 78             | 26     | 9      | name.com  |
| ada.rsvp        | premium   | $623.75   | —             | 62             | 52     | 3      | name.com  |
| awaken.rsvp     | available | $14.99    | —             | 76             | 26     | 6      | name.com  |
| info.rsvp       | premium   | $623.75   | —             | 80             | 51     | 4      | name.com  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,792 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/rsvp?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_rsvp_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/rsvp?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_rsvp_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_rsvp_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of one-word .rsvp domains. That makes relevance to invitations, attendance, events, guest lists, launches, and private access the main lens for evaluation. Some names are literal and event-ready, such as carnival.rsvp, while others are broader or more abstract, such as inside.rsvp or alabaster.rsvp. When comparing these domains, focus on whether the word gains clarity from the .rsvp ending or becomes awkward with it. The median ask is 71.89, which keeps price discipline important, but fit matters more than novelty in a niche extension like .rsvp.

- Favor words that read naturally before .rsvp
- Check if the term fits events, access, or response
- Use price discipline around the 71.89 median ask
- Watch for trademark-heavy words like einstein.rsvp

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .RSVP One-Word Domains*. Version 2026-06-04. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .RSVP page](https://unique.domains/domains/tld/rsvp?utm_source=github&utm_medium=referral&utm_campaign=repo_rsvp_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_rsvp_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_rsvp_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_rsvp_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
