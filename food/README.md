# Jedlo (Food & Nutrition)

2 datasets — 4,802 records

> Browse at [listbase.org/sk/food/](https://listbase.org/sk/food/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Slovenské reštaurácie](sk-restauracie.json) | 4,552 | 455 KB | [CSV](sk-restauracie_SK.csv) | [Excel](sk-restauracie_SK.xlsx) | [View](https://listbase.org/sk/food/sk-restauracie/) |
| [Slovenské vinotéky](sk-vinoteky.json) | 250 | 27 KB | [CSV](sk-vinoteky_SK.csv) | [Excel](sk-vinoteky_SK.xlsx) | [View](https://listbase.org/sk/food/sk-vinoteky/) |

## Quick Start

```bash
# List all food & nutrition datasets
curl https://cdn.sk.listbase.org/index.json | jq '.datasets[] | select(.category=="food") | .id'

# Fetch a dataset
curl https://cdn.sk.listbase.org/food/sk-restauracie.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/sk/food/)
