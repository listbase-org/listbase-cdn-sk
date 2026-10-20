# Kultúra a náboženstvo (Culture & Religion)

10 datasets — 1,365 records

> Browse at [listbase.org/sk/culture/](https://listbase.org/sk/culture/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Kostoly na Slovensku](sk-kostoly.json) | 370 | 2604 KB | [CSV](sk-kostoly_SK.csv) | [Excel](sk-kostoly_SK.xlsx) | [View](https://listbase.org/sk/culture/sk-kostoly/) |
| [Cintoríny na Slovensku](sk-cintoriny.json) | 319 | 393 KB | [CSV](sk-cintoriny_SK.csv) | [Excel](sk-cintoriny_SK.xlsx) | [View](https://listbase.org/sk/culture/sk-cintoriny/) |
| [Múzeá na Slovensku (Museums in Slovakia)](sk-muzea.json) | 205 | 146 KB | [CSV](sk-muzea_SK.csv) | [Excel](sk-muzea_SK.xlsx) | [View](https://listbase.org/sk/culture/sk-muzea/) |
| [Múzeá na Slovensku – OpenStreetMap (Museums in Slovakia, OSM)](sk-osm-muzea.json) | 183 | 41 KB | [CSV](sk-osm-muzea_SK.csv) | [Excel](sk-osm-muzea_SK.xlsx) | [View](https://listbase.org/sk/culture/sk-osm-muzea/) |
| [Sk Klastory](sk-klastory.json) | 100 | 139 KB | [CSV](sk-klastory_SK.csv) | [Excel](sk-klastory_SK.xlsx) | [View](https://listbase.org/sk/culture/sk-klastory/) |
| [Záhrady na Slovensku (Historical gardens of Slovakia)](sk-zahrady.json) | 100 | 132 KB | [CSV](sk-zahrady_SK.csv) | [Excel](sk-zahrady_SK.xlsx) | [View](https://listbase.org/sk/culture/sk-zahrady/) |
| [Divadlá na Slovensku (Theatres in Slovakia)](sk-divadla.json) | 44 | 40 KB | [CSV](sk-divadla_SK.csv) | [Excel](sk-divadla_SK.xlsx) | [View](https://listbase.org/sk/culture/sk-divadla/) |
| [Drevené kostoly Slovenska (Slovak wooden churches)](sk-drevene-kostoly.json) | 22 | 132 KB | [CSV](sk-drevene-kostoly_SK.csv) | [Excel](sk-drevene-kostoly_SK.xlsx) | [View](https://listbase.org/sk/culture/sk-drevene-kostoly/) |
| [Katedrály na Slovensku](sk-katedraly.json) | 15 | 171 KB | [CSV](sk-katedraly_SK.csv) | [Excel](sk-katedraly_SK.xlsx) | [View](https://listbase.org/sk/culture/sk-katedraly/) |
| [Svetové dedičstvo UNESCO na Slovensku](sk-svetove-dedicstvo-unesco.json) | 7 | 9 KB | [CSV](sk-svetove-dedicstvo-unesco_SK.csv) | [Excel](sk-svetove-dedicstvo-unesco_SK.xlsx) | [View](https://listbase.org/sk/culture/sk-svetove-dedicstvo-unesco/) |

## Quick Start

```bash
# List all culture & religion datasets
curl https://cdn.sk.listbase.org/index.json | jq '.datasets[] | select(.category=="culture") | .id'

# Fetch a dataset
curl https://cdn.sk.listbase.org/culture/sk-kostoly.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/sk/culture/)
