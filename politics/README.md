# Politika (Politics)

2 datasets — 20 records

> Browse at [listbase.org/sk/politics/](https://listbase.org/sk/politics/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Predsedovia Národnej rady Slovenskej republiky](sk-predsedovia-narodnej-rady.json) | 11 | 11 KB | [CSV](sk-predsedovia-narodnej-rady_SK.csv) | [Excel](sk-predsedovia-narodnej-rady_SK.xlsx) | [View](https://listbase.org/sk/politics/sk-predsedovia-narodnej-rady/) |
| [Prezidenti Slovenska / Presidents of Slovakia](sk-prezidenti.json) | 9 | 11 KB | [CSV](sk-prezidenti_SK.csv) | [Excel](sk-prezidenti_SK.xlsx) | [View](https://listbase.org/sk/politics/sk-prezidenti/) |

## Quick Start

```bash
# List all politics datasets
curl https://cdn.sk.listbase.org/index.json | jq '.datasets[] | select(.category=="politics") | .id'

# Fetch a dataset
curl https://cdn.sk.listbase.org/politics/sk-predsedovia-narodnej-rady.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/sk/politics/)
