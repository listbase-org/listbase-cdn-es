# Idioma (Language)

1 datasets — 131 records

> Browse at [listbase.org/es/language/](https://listbase.org/es/language/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Sistemas de escritura del mundo (ISO 15924 / CLDR en español)](es-sistemas-de-escritura.json) | 131 | 12 KB | [CSV](es-sistemas-de-escritura_ES.csv) | [Excel](es-sistemas-de-escritura_ES.xlsx) | [View](https://listbase.org/es/language/es-sistemas-de-escritura/) |

## Quick Start

```bash
# List all language datasets
curl https://cdn.es.listbase.org/index.json | jq '.datasets[] | select(.category=="language") | .id'

# Fetch a dataset
curl https://cdn.es.listbase.org/language/es-sistemas-de-escritura.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/es/language/)
