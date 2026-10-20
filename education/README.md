# Vzdelávanie (Education)

4 datasets — 5,695 records

> Browse at [listbase.org/sk/education/](https://listbase.org/sk/education/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Školy na Slovensku (ZŠ a SŠ)](sk-skoly.json) | 3,410 | 1313 KB | [CSV](sk-skoly_SK.csv) | [Excel](sk-skoly_SK.xlsx) | [View](https://listbase.org/sk/education/sk-skoly/) |
| [Školy (OSM)](sk-osm-skoly.json) | 2,119 | 254 KB | [CSV](sk-osm-skoly_SK.csv) | [Excel](sk-osm-skoly_SK.xlsx) | [View](https://listbase.org/sk/education/sk-osm-skoly/) |
| [Typy škôl (číselník RIS)](sk-skoly-typy.json) | 135 | 16 KB | [CSV](sk-skoly-typy_SK.csv) | [Excel](sk-skoly-typy_SK.xlsx) | [View](https://listbase.org/sk/education/sk-skoly-typy/) |
| [Slovakia — Universities (univerzity)](sk-univerzity.json) | 31 | 11 KB | [CSV](sk-univerzity_SK.csv) | [Excel](sk-univerzity_SK.xlsx) | [View](https://listbase.org/sk/education/sk-univerzity/) |

## Quick Start

```bash
# List all education datasets
curl https://cdn.sk.listbase.org/index.json | jq '.datasets[] | select(.category=="education") | .id'

# Fetch a dataset
curl https://cdn.sk.listbase.org/education/sk-skoly.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/sk/education/)
