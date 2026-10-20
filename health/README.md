# Zdravie (Health)

2 datasets — 1,570 records

> Browse at [listbase.org/sk/health/](https://listbase.org/sk/health/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Lekárne na Slovensku – OpenStreetMap (Pharmacies in Slovakia, OSM)](sk-lekarne.json) | 1,450 | 144 KB | [CSV](sk-lekarne_SK.csv) | [Excel](sk-lekarne_SK.xlsx) | [View](https://listbase.org/sk/health/sk-lekarne/) |
| [Nemocnice na Slovensku – OpenStreetMap (Hospitals in Slovakia, OSM)](sk-nemocnice.json) | 120 | 16 KB | [CSV](sk-nemocnice_SK.csv) | [Excel](sk-nemocnice_SK.xlsx) | [View](https://listbase.org/sk/health/sk-nemocnice/) |

## Quick Start

```bash
# List all health datasets
curl https://cdn.sk.listbase.org/index.json | jq '.datasets[] | select(.category=="health") | .id'

# Fetch a dataset
curl https://cdn.sk.listbase.org/health/sk-lekarne.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/sk/health/)
