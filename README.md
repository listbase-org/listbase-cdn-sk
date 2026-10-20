# ListBase CDN — Slovenčina (sk)

Open dataset collection for **Slovenčina** (Slovak).
411 datasets across 18 categories with 277,884 total records.

> Browse and download at [https://listbase.org/sk/](https://listbase.org/sk/)

## Categories

| Category | Datasets |
|----------|----------|
| [Kultúra a náboženstvo (Culture & Religion)](culture/) | 10 |
| [Vzdelávanie (Education)](education/) | 4 |
| [Zábava (Entertainment)](entertainment/) | 2 |
| [Životné prostredie (Environment)](environment/) | 6 |
| [Financie a obchod (Finance & Trade)](finance/) | 4 |
| [Jedlo (Food & Nutrition)](food/) | 2 |
| [Geografia (Geography)](geography/) | 47 |
| [Zdravie (Health)](health/) | 2 |
| [História (History)](history/) | 1 |
| [Jazyk (Language)](language/) | 5 |
| [Politika (Politics)](politics/) | 2 |
| [Referencia (Reference)](reference/) | 265 |
| [Šport (Sports)](sports/) | 3 |
| [Technológia (Technology)](tech/) | 12 |
| [Čas a kalendár (Time & Calendar)](time/) | 6 |
| [Turizmus (Tourism)](tourism/) | 2 |
| [Doprava (Transport)](transport/) | 17 |
| [Jednotky a miery (Units & Measurements)](units/) | 21 |

## Usage

### Browse on the web
Visit [listbase.org/sk/](https://listbase.org/sk/) to search, preview, and download in Excel, CSV, or PDF.

### Fetch via CDN
```bash
# Dataset index (metadata only)
curl https://cdn.sk.listbase.org/index.json

# Full dataset (JSON)
curl https://cdn.sk.listbase.org/geography/th-central-provinces.json

# Download as Excel or CSV
curl -O https://cdn.sk.listbase.org/geography/th-central-provinces_SK.xlsx
curl -O https://cdn.sk.listbase.org/geography/th-central-provinces_SK.csv

# Build dump (metadata + sample rows, gzipped)
curl https://cdn.sk.listbase.org/dump.json.gz | gunzip
```

### Use in JavaScript
```js
const res = await fetch('https://cdn.sk.listbase.org/geography/th-central-provinces.json');
const data = await res.json();
console.log(data.name);    // "ภาคกลาง — จังหวัดในภาคกลาง"
console.log(data.rows);    // [{ ... }, ...]
```

## File Structure

```
├── index.json              # Dataset index (metadata + file info)
├── dump.json.gz            # Build dump (metadata + 20 sample rows per dataset)
├── {category}/
│   ├── README.md           # Category overview
│   ├── {dataset}.json      # Full dataset with rows
│   ├── {dataset}_SK.csv   # CSV download
│   └── {dataset}_SK.xlsx  # Excel download
```

## Dataset JSON Format

Each `.json` file contains:

| Field | Description |
|-------|-------------|
| `id` | Unique dataset identifier |
| `name` | Dataset name |
| `description` | What this dataset contains |
| `category` | Category (e.g. geography, finance) |
| `source` | Data source attribution |
| `updated` | Last updated date |
| `record_count` | Number of records |
| `columns` | Column definitions (key, label, type) |
| `rows` | Array of data records |

## License

Data is provided under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
See individual dataset `source` fields for original data attribution.

---

Part of [ListBase](https://listbase.org) — Free Reference Tables & Lists
