# História (History)

1 datasets — 167 records

> Browse at [listbase.org/sk/history/](https://listbase.org/sk/history/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Archeologicke lokality na Slovensku (Archaeological sites in Slovakia)](sk-archeologicke-lokality.json) | 167 | 118 KB | [CSV](sk-archeologicke-lokality_SK.csv) | [Excel](sk-archeologicke-lokality_SK.xlsx) | [View](https://listbase.org/sk/history/sk-archeologicke-lokality/) |

## Quick Start

```bash
# List all history datasets
curl https://cdn.sk.listbase.org/index.json | jq '.datasets[] | select(.category=="history") | .id'

# Fetch a dataset
curl https://cdn.sk.listbase.org/history/sk-archeologicke-lokality.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/sk/history/)
