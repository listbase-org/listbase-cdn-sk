# Technológia (Technology)

12 datasets — 3,459 records

> Browse at [listbase.org/sk/tech/](https://listbase.org/sk/tech/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Emoji — názvy v slovenčine (CLDR)](sk-nazvy-emoji.json) | 1,966 | 351 KB | [CSV](sk-nazvy-emoji_SK.csv) | [Excel](sk-nazvy-emoji_SK.xlsx) | [View](https://listbase.org/sk/tech/sk-nazvy-emoji/) |
| [Knižnice na Slovensku – OpenStreetMap (Libraries in Slovakia, OSM)](sk-kniznice.json) | 1,131 | 133 KB | [CSV](sk-kniznice_SK.csv) | [Excel](sk-kniznice_SK.xlsx) | [View](https://listbase.org/sk/tech/sk-kniznice/) |
| [Časové pásma sveta (IANA / CLDR slovenčina)](sk-casove-pasma.json) | 181 | 32 KB | [CSV](sk-casove-pasma_SK.csv) | [Excel](sk-casove-pasma_SK.xlsx) | [View](https://listbase.org/sk/tech/sk-casove-pasma/) |
| [Časové pásma — Asia (56)](sk-casove-pasma-asia.json) | 56 | 10 KB | [CSV](sk-casove-pasma-asia_SK.csv) | [Excel](sk-casove-pasma-asia_SK.xlsx) | [View](https://listbase.org/sk/tech/sk-casove-pasma-asia/) |
| [Časové pásma — America (49)](sk-casove-pasma-america.json) | 49 | 10 KB | [CSV](sk-casove-pasma-america_SK.csv) | [Excel](sk-casove-pasma-america_SK.xlsx) | [View](https://listbase.org/sk/tech/sk-casove-pasma-america/) |
| [Časové pásma — Europe (32)](sk-casove-pasma-europe.json) | 32 | 7 KB | [CSV](sk-casove-pasma-europe_SK.csv) | [Excel](sk-casove-pasma-europe_SK.xlsx) | [View](https://listbase.org/sk/tech/sk-casove-pasma-europe/) |
| [Časové pásma — Africa (14)](sk-casove-pasma-africa.json) | 14 | 4 KB | [CSV](sk-casove-pasma-africa_SK.csv) | [Excel](sk-casove-pasma-africa_SK.xlsx) | [View](https://listbase.org/sk/tech/sk-casove-pasma-africa/) |
| [Časové pásma — Pacific (10)](sk-casove-pasma-pacific.json) | 10 | 3 KB | [CSV](sk-casove-pasma-pacific_SK.csv) | [Excel](sk-casove-pasma-pacific_SK.xlsx) | [View](https://listbase.org/sk/tech/sk-casove-pasma-pacific/) |
| [Časové pásma — Atlantic (8)](sk-casove-pasma-atlantic.json) | 8 | 3 KB | [CSV](sk-casove-pasma-atlantic_SK.csv) | [Excel](sk-casove-pasma-atlantic_SK.xlsx) | [View](https://listbase.org/sk/tech/sk-casove-pasma-atlantic/) |
| [Časové pásma — Indian (8)](sk-casove-pasma-indian.json) | 8 | 3 KB | [CSV](sk-casove-pasma-indian_SK.csv) | [Excel](sk-casove-pasma-indian_SK.xlsx) | [View](https://listbase.org/sk/tech/sk-casove-pasma-indian/) |
| [Časové pásma — Antarctica (2)](sk-casove-pasma-antarctica.json) | 2 | 2 KB | [CSV](sk-casove-pasma-antarctica_SK.csv) | [Excel](sk-casove-pasma-antarctica_SK.xlsx) | [View](https://listbase.org/sk/tech/sk-casove-pasma-antarctica/) |
| [Časové pásma — Etc (2)](sk-casove-pasma-etc.json) | 2 | 2 KB | [CSV](sk-casove-pasma-etc_SK.csv) | [Excel](sk-casove-pasma-etc_SK.xlsx) | [View](https://listbase.org/sk/tech/sk-casove-pasma-etc/) |

## Quick Start

```bash
# List all technology datasets
curl https://cdn.sk.listbase.org/index.json | jq '.datasets[] | select(.category=="tech") | .id'

# Fetch a dataset
curl https://cdn.sk.listbase.org/tech/sk-nazvy-emoji.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/sk/tech/)
