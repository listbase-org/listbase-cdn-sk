# Jazyk (Language)

5 datasets — 54,220 records

> Browse at [listbase.org/sk/language/](https://listbase.org/sk/language/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Slovenské podstatné mená — zoznam (24,891 slov)](sk-podstatne-mena.json) | 24,891 | 1545 KB | [CSV](sk-podstatne-mena_SK.csv) | [Excel](sk-podstatne-mena_SK.xlsx) | [View](https://listbase.org/sk/language/sk-podstatne-mena/) |
| [Slovenské prídavné mená — zoznam (14,694 slov)](sk-pridavne-mena.json) | 14,694 | 933 KB | [CSV](sk-pridavne-mena_SK.csv) | [Excel](sk-pridavne-mena_SK.xlsx) | [View](https://listbase.org/sk/language/sk-pridavne-mena/) |
| [Slovenské slovesá — zoznam (13,955 slov)](sk-slovesa.json) | 13,955 | 876 KB | [CSV](sk-slovesa_SK.csv) | [Excel](sk-slovesa_SK.xlsx) | [View](https://listbase.org/sk/language/sk-slovesa/) |
| [Jazyky sveta](sk-jazyky.json) | 609 | 59 KB | [CSV](sk-jazyky_SK.csv) | [Excel](sk-jazyky_SK.xlsx) | [View](https://listbase.org/sk/language/sk-jazyky/) |
| [Systémy písma sveta (ISO 15924 / CLDR slovenčina)](sk-systemy-pisma.json) | 71 | 7 KB | [CSV](sk-systemy-pisma_SK.csv) | [Excel](sk-systemy-pisma_SK.xlsx) | [View](https://listbase.org/sk/language/sk-systemy-pisma/) |

## Quick Start

```bash
# List all language datasets
curl https://cdn.sk.listbase.org/index.json | jq '.datasets[] | select(.category=="language") | .id'

# Fetch a dataset
curl https://cdn.sk.listbase.org/language/sk-podstatne-mena.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/sk/language/)
