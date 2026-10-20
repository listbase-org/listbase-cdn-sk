# Šport (Sports)

3 datasets — 2,406 records

> Browse at [listbase.org/sk/sports/](https://listbase.org/sk/sports/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Liga majstrov UEFA — všetky zápasy hlavnej súťaže 2011/12–2025/26 (1997)](sk-liga-majstrov-uefa-zapasy.json) | 1,997 | 1126 KB | [CSV](sk-liga-majstrov-uefa-zapasy_SK.csv) | [Excel](sk-liga-majstrov-uefa-zapasy_SK.xlsx) | [View](https://listbase.org/sk/sports/sk-liga-majstrov-uefa-zapasy/) |
| [Slovenské športové predajne](sk-sportove-predajne.json) | 335 | 34 KB | [CSV](sk-sportove-predajne_SK.csv) | [Excel](sk-sportove-predajne_SK.xlsx) | [View](https://listbase.org/sk/sports/sk-sportove-predajne/) |
| [Slovenské kluby v pohároch UEFA — zápasy 2021/22–2025/26 (74)](sk-slovenske-kluby-v-poharoch-uefa-zapasy.json) | 74 | 47 KB | [CSV](sk-slovenske-kluby-v-poharoch-uefa-zapasy_SK.csv) | [Excel](sk-slovenske-kluby-v-poharoch-uefa-zapasy_SK.xlsx) | [View](https://listbase.org/sk/sports/sk-slovenske-kluby-v-poharoch-uefa-zapasy/) |

## Quick Start

```bash
# List all sports datasets
curl https://cdn.sk.listbase.org/index.json | jq '.datasets[] | select(.category=="sports") | .id'

# Fetch a dataset
curl https://cdn.sk.listbase.org/sports/sk-liga-majstrov-uefa-zapasy.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/sk/sports/)
