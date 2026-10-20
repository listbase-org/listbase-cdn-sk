# Doprava (Transport)

17 datasets — 1,930 records

> Browse at [listbase.org/sk/transport/](https://listbase.org/sk/transport/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Železničné stanice na Slovensku (Railway stations in Slovakia)](sk-zeleznicne-stanice.json) | 606 | 358 KB | [CSV](sk-zeleznicne-stanice_SK.csv) | [Excel](sk-zeleznicne-stanice_SK.xlsx) | [View](https://listbase.org/sk/transport/sk-zeleznicne-stanice/) |
| [Kódy UN/LOCODE — Slovensko (prístavy, letiská, terminály)](sk-unlocode.json) | 555 | 369 KB | [CSV](sk-unlocode_SK.csv) | [Excel](sk-unlocode_SK.xlsx) | [View](https://listbase.org/sk/transport/sk-unlocode/) |
| [Letiská na Slovensku (kompletný zoznam)](sk-letiska.json) | 129 | 83 KB | [CSV](sk-letiska_SK.csv) | [Excel](sk-letiska_SK.xlsx) | [View](https://listbase.org/sk/transport/sk-letiska/) |
| [Mosty na Slovensku](sk-historicke-mosty.json) | 114 | 144 KB | [CSV](sk-historicke-mosty_SK.csv) | [Excel](sk-historicke-mosty_SK.xlsx) | [View](https://listbase.org/sk/transport/sk-historicke-mosty/) |
| [Kódy UN/LOCODE — Nitriansky kraj](sk-nitriansky-unlocode.json) | 75 | 72 KB | [CSV](sk-nitriansky-unlocode_SK.csv) | [Excel](sk-nitriansky-unlocode_SK.xlsx) | [View](https://listbase.org/sk/transport/sk-nitriansky-unlocode/) |
| [Kódy UN/LOCODE — Trnavský kraj](sk-trnavsky-unlocode.json) | 75 | 72 KB | [CSV](sk-trnavsky-unlocode_SK.csv) | [Excel](sk-trnavsky-unlocode_SK.xlsx) | [View](https://listbase.org/sk/transport/sk-trnavsky-unlocode/) |
| [Kódy UN/LOCODE — Trenčiansky kraj](sk-trenciansky-unlocode.json) | 53 | 52 KB | [CSV](sk-trenciansky-unlocode_SK.csv) | [Excel](sk-trenciansky-unlocode_SK.xlsx) | [View](https://listbase.org/sk/transport/sk-trenciansky-unlocode/) |
| [Kódy UN/LOCODE — Banskobystrický kraj](sk-banskobystricky-unlocode.json) | 50 | 51 KB | [CSV](sk-banskobystricky-unlocode_SK.csv) | [Excel](sk-banskobystricky-unlocode_SK.xlsx) | [View](https://listbase.org/sk/transport/sk-banskobystricky-unlocode/) |
| [Kódy UN/LOCODE — Prešovský kraj](sk-presovsky-unlocode.json) | 48 | 47 KB | [CSV](sk-presovsky-unlocode_SK.csv) | [Excel](sk-presovsky-unlocode_SK.xlsx) | [View](https://listbase.org/sk/transport/sk-presovsky-unlocode/) |
| [Kódy UN/LOCODE — Žilinský kraj](sk-zilinsky-unlocode.json) | 47 | 46 KB | [CSV](sk-zilinsky-unlocode_SK.csv) | [Excel](sk-zilinsky-unlocode_SK.xlsx) | [View](https://listbase.org/sk/transport/sk-zilinsky-unlocode/) |
| [Kódy UN/LOCODE — Košický kraj](sk-kosicky-unlocode.json) | 41 | 40 KB | [CSV](sk-kosicky-unlocode_SK.csv) | [Excel](sk-kosicky-unlocode_SK.xlsx) | [View](https://listbase.org/sk/transport/sk-kosicky-unlocode/) |
| [Vzletové a pristávacie dráhy na Slovensku](sk-vzletove-drahy.json) | 41 | 36 KB | [CSV](sk-vzletove-drahy_SK.csv) | [Excel](sk-vzletove-drahy_SK.xlsx) | [View](https://listbase.org/sk/transport/sk-vzletove-drahy/) |
| [Letiská na Slovensku (Airports of Slovakia)](sk-letiska-aerodb.json) | 33 | 18 KB | [CSV](sk-letiska-aerodb_SK.csv) | [Excel](sk-letiska-aerodb_SK.xlsx) | [View](https://listbase.org/sk/transport/sk-letiska-aerodb/) |
| [Kódy UN/LOCODE — Bratislavský kraj](sk-bratislavsky-unlocode.json) | 29 | 30 KB | [CSV](sk-bratislavsky-unlocode_SK.csv) | [Excel](sk-bratislavsky-unlocode_SK.xlsx) | [View](https://listbase.org/sk/transport/sk-bratislavsky-unlocode/) |
| [Rádionavigačné zariadenia na Slovensku](sk-radionavigacne-zariadenia.json) | 21 | 18 KB | [CSV](sk-radionavigacne-zariadenia_SK.csv) | [Excel](sk-radionavigacne-zariadenia_SK.xlsx) | [View](https://listbase.org/sk/transport/sk-radionavigacne-zariadenia/) |
| [IATA/ICAO kódy letísk Slovenska](sk-iata-icao-letiska.json) | 8 | 3 KB | [CSV](sk-iata-icao-letiska_SK.csv) | [Excel](sk-iata-icao-letiska_SK.xlsx) | [View](https://listbase.org/sk/transport/sk-iata-icao-letiska/) |
| [Medzinárodné letiská na Slovensku (International Airports of Slovakia)](sk-medzinarodne-letiska.json) | 5 | 5 KB | [CSV](sk-medzinarodne-letiska_SK.csv) | [Excel](sk-medzinarodne-letiska_SK.xlsx) | [View](https://listbase.org/sk/transport/sk-medzinarodne-letiska/) |

## Quick Start

```bash
# List all transport datasets
curl https://cdn.sk.listbase.org/index.json | jq '.datasets[] | select(.category=="transport") | .id'

# Fetch a dataset
curl https://cdn.sk.listbase.org/transport/sk-zeleznicne-stanice.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/sk/transport/)
