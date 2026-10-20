# Zábava (Entertainment)

2 datasets — 473 records

> Browse at [listbase.org/sk/entertainment/](https://listbase.org/sk/entertainment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Slovak films (sk-filmy)](sk-filmy.json) | 270 | 2749 KB | [CSV](sk-filmy_SK.csv) | [Excel](sk-filmy_SK.xlsx) | [View](https://listbase.org/sk/entertainment/sk-filmy/) |
| [Slovenské kníhkupectvá](sk-knihkupectva.json) | 203 | 21 KB | [CSV](sk-knihkupectva_SK.csv) | [Excel](sk-knihkupectva_SK.xlsx) | [View](https://listbase.org/sk/entertainment/sk-knihkupectva/) |

## Quick Start

```bash
# List all entertainment datasets
curl https://cdn.sk.listbase.org/index.json | jq '.datasets[] | select(.category=="entertainment") | .id'

# Fetch a dataset
curl https://cdn.sk.listbase.org/entertainment/sk-filmy.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/sk/entertainment/)
