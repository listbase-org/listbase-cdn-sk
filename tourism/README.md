# Turizmus (Tourism)

2 datasets — 1,889 records

> Browse at [listbase.org/sk/tourism/](https://listbase.org/sk/tourism/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Hotely na Slovensku](sk-hotely.json) | 1,038 | 105 KB | [CSV](sk-hotely_SK.csv) | [Excel](sk-hotely_SK.xlsx) | [View](https://listbase.org/sk/tourism/sk-hotely/) |
| [Slovenské turistické atrakcie](sk-atrakcie.json) | 851 | 93 KB | [CSV](sk-atrakcie_SK.csv) | [Excel](sk-atrakcie_SK.xlsx) | [View](https://listbase.org/sk/tourism/sk-atrakcie/) |

## Quick Start

```bash
# List all tourism datasets
curl https://cdn.sk.listbase.org/index.json | jq '.datasets[] | select(.category=="tourism") | .id'

# Fetch a dataset
curl https://cdn.sk.listbase.org/tourism/sk-hotely.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/sk/tourism/)
