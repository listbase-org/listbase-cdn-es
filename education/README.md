# Educación (Education)

1 datasets — 96 records

> Browse at [listbase.org/es/education/](https://listbase.org/es/education/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [España — Universidades e instituciones de educación superior](es-universidades.json) | 96 | 30 KB | [CSV](es-universidades_ES.csv) | [Excel](es-universidades_ES.xlsx) | [View](https://listbase.org/es/education/es-universidades/) |

## Quick Start

```bash
# List all education datasets
curl https://cdn.es.listbase.org/index.json | jq '.datasets[] | select(.category=="education") | .id'

# Fetch a dataset
curl https://cdn.es.listbase.org/education/es-universidades.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/es/education/)
