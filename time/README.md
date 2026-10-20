# Čas a kalendár (Time & Calendar)

6 datasets — 1,761 records

> Browse at [listbase.org/sk/time/](https://listbase.org/sk/time/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Štátne sviatky a pamätné dni Slovenskej republiky (1993–2030)](sk-statne-sviatky.json) | 569 | 272 KB | [CSV](sk-statne-sviatky_SK.csv) | [Excel](sk-statne-sviatky_SK.xlsx) | [View](https://listbase.org/sk/time/sk-statne-sviatky/) |
| [Slovenské štátne sviatky a pamätné dni — všetky kategórie (1993–2030)](sk-statne-sviatky-vsetky-kategorie.json) | 569 | 1243 KB | [CSV](sk-statne-sviatky-vsetky-kategorie_SK.csv) | [Excel](sk-statne-sviatky-vsetky-kategorie_SK.xlsx) | [View](https://listbase.org/sk/time/sk-statne-sviatky-vsetky-kategorie/) |
| [Slovenské meniny (Slovak Name-Day Calendar)](sk-meniny.json) | 366 | 85 KB | [CSV](sk-meniny_SK.csv) | [Excel](sk-meniny_SK.xlsx) | [View](https://listbase.org/sk/time/sk-meniny/) |
| [Slovenské štátne sviatky (multijazyčné, openpotato/OpenHolidays)](sk-statne-sviatky-multijazycne.json) | 159 | 77 KB | [CSV](sk-statne-sviatky-multijazycne_SK.csv) | [Excel](sk-statne-sviatky-multijazycne_SK.xlsx) | [View](https://listbase.org/sk/time/sk-statne-sviatky-multijazycne/) |
| [Názvy mesiacov podľa kalendára (CLDR slovenčina)](sk-mesiace-kalendara.json) | 74 | 13 KB | [CSV](sk-mesiace-kalendara_SK.csv) | [Excel](sk-mesiace-kalendara_SK.xlsx) | [View](https://listbase.org/sk/time/sk-mesiace-kalendara/) |
| [Dni, štvrťroky, časti dňa a éry — názvy v slovenčine (CLDR)](sk-dni-stvrtroky-ery.json) | 24 | 5 KB | [CSV](sk-dni-stvrtroky-ery_SK.csv) | [Excel](sk-dni-stvrtroky-ery_SK.xlsx) | [View](https://listbase.org/sk/time/sk-dni-stvrtroky-ery/) |

## Quick Start

```bash
# List all time & calendar datasets
curl https://cdn.sk.listbase.org/index.json | jq '.datasets[] | select(.category=="time") | .id'

# Fetch a dataset
curl https://cdn.sk.listbase.org/time/sk-statne-sviatky.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/sk/time/)
