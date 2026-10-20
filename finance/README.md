# Financie a obchod (Finance & Trade)

4 datasets — 3,528 records

> Browse at [listbase.org/sk/finance/](https://listbase.org/sk/finance/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Dlh obcí a organizácií Slovenska (2015–2021)](sk-obce-dlh.json) | 2,926 | 889 KB | [CSV](sk-obce-dlh_SK.csv) | [Excel](sk-obce-dlh_SK.xlsx) | [View](https://listbase.org/sk/finance/sk-obce-dlh/) |
| [Stavebniny a veľkoobchody](sk-stavebniny.json) | 358 | 38 KB | [CSV](sk-stavebniny_SK.csv) | [Excel](sk-stavebniny_SK.xlsx) | [View](https://listbase.org/sk/finance/sk-stavebniny/) |
| [Banky na Slovensku — BIC/SWIFT kódy](sk-banky-bic.json) | 122 | 44 KB | [CSV](sk-banky-bic_SK.csv) | [Excel](sk-banky-bic_SK.xlsx) | [View](https://listbase.org/sk/finance/sk-banky-bic/) |
| [SWIFT/BIC kódy — Slovensko](sk-swift-kody.json) | 122 | 20 KB | [CSV](sk-swift-kody_SK.csv) | [Excel](sk-swift-kody_SK.xlsx) | [View](https://listbase.org/sk/finance/sk-swift-kody/) |

## Quick Start

```bash
# List all finance & trade datasets
curl https://cdn.sk.listbase.org/index.json | jq '.datasets[] | select(.category=="finance") | .id'

# Fetch a dataset
curl https://cdn.sk.listbase.org/finance/sk-obce-dlh.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/sk/finance/)
