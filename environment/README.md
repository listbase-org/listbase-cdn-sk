# Životné prostredie (Environment)

6 datasets — 908 records

> Browse at [listbase.org/sk/environment/](https://listbase.org/sk/environment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Prírodné rezervácie na Slovensku — Nature reserves of Slovakia](sk-prirodne-rezervacie.json) | 629 | 1498 KB | [CSV](sk-prirodne-rezervacie_SK.csv) | [Excel](sk-prirodne-rezervacie_SK.xlsx) | [View](https://listbase.org/sk/environment/sk-prirodne-rezervacie/) |
| [Elektrárne na Slovensku](sk-elektrarne.json) | 232 | 123 KB | [CSV](sk-elektrarne_SK.csv) | [Excel](sk-elektrarne_SK.xlsx) | [View](https://listbase.org/sk/environment/sk-elektrarne/) |
| [Vodné elektrárne na Slovensku](sk-vodne-elektrarne.json) | 19 | 29 KB | [CSV](sk-vodne-elektrarne_SK.csv) | [Excel](sk-vodne-elektrarne_SK.xlsx) | [View](https://listbase.org/sk/environment/sk-vodne-elektrarne/) |
| [Merné jednotky — kategória 'energy' (14)](sk-merne-jednotky-energy.json) | 14 | 4 KB | [CSV](sk-merne-jednotky-energy_SK.csv) | [Excel](sk-merne-jednotky-energy_SK.xlsx) | [View](https://listbase.org/sk/environment/sk-merne-jednotky-energy/) |
| [Jadrové elektrárne na Slovensku](sk-jadrove-elektrarne.json) | 9 | 7 KB | [CSV](sk-jadrove-elektrarne_SK.csv) | [Excel](sk-jadrove-elektrarne_SK.xlsx) | [View](https://listbase.org/sk/environment/sk-jadrove-elektrarne/) |
| [Merné jednotky — kategória 'temperature' (5)](sk-merne-jednotky-temperature.json) | 5 | 3 KB | [CSV](sk-merne-jednotky-temperature_SK.csv) | [Excel](sk-merne-jednotky-temperature_SK.xlsx) | [View](https://listbase.org/sk/environment/sk-merne-jednotky-temperature/) |

## Quick Start

```bash
# List all environment datasets
curl https://cdn.sk.listbase.org/index.json | jq '.datasets[] | select(.category=="environment") | .id'

# Fetch a dataset
curl https://cdn.sk.listbase.org/environment/sk-prirodne-rezervacie.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/sk/environment/)
