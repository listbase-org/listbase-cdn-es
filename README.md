# ListBase CDN — Español (es)

Open dataset collection for **Español** (Spanish).
464 datasets across 13 categories with 418,799 total records.

> Browse and download at [https://listbase.org/es/](https://listbase.org/es/)

## Categories

| Category | Datasets |
|----------|----------|
| [Cultura y religión (Culture & Religion)](culture/) | 2 |
| [Educación (Education)](education/) | 1 |
| [Medio ambiente (Environment)](environment/) | 4 |
| [Finanzas y comercio (Finance & Trade)](finance/) | 21 |
| [Comida (Food & Nutrition)](food/) | 1 |
| [Geografía (Geography)](geography/) | 10 |
| [Salud (Health)](health/) | 23 |
| [Idioma (Language)](language/) | 1 |
| [Referencia (Reference)](reference/) | 341 |
| [Tecnología (Technology)](tech/) | 12 |
| [Tiempo y calendario (Time & Calendar)](time/) | 2 |
| [Transporte (Transport)](transport/) | 25 |
| [Unidades y medidas (Units & Measurements)](units/) | 21 |

## Usage

### Browse on the web
Visit [listbase.org/es/](https://listbase.org/es/) to search, preview, and download in Excel, CSV, or PDF.

### Fetch via CDN
```bash
# Dataset index (metadata only)
curl https://cdn.es.listbase.org/index.json

# Full dataset (JSON)
curl https://cdn.es.listbase.org/geography/th-central-provinces.json

# Download as Excel or CSV
curl -O https://cdn.es.listbase.org/geography/th-central-provinces_ES.xlsx
curl -O https://cdn.es.listbase.org/geography/th-central-provinces_ES.csv

# Build dump (metadata + sample rows, gzipped)
curl https://cdn.es.listbase.org/dump.json.gz | gunzip
```

### Use in JavaScript
```js
const res = await fetch('https://cdn.es.listbase.org/geography/th-central-provinces.json');
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
│   ├── {dataset}_ES.csv   # CSV download
│   └── {dataset}_ES.xlsx  # Excel download
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
