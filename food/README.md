# Comida (Food & Nutrition)

1 datasets — 1,302 records

> Browse at [listbase.org/es/food/](https://listbase.org/es/food/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Restaurantes de la Guía Michelin en España](es-restaurantes-michelin.json) | 1,302 | 1583 KB | [CSV](es-restaurantes-michelin_ES.csv) | [Excel](es-restaurantes-michelin_ES.xlsx) | [View](https://listbase.org/es/food/es-restaurantes-michelin/) |

## Quick Start

```bash
# List all food & nutrition datasets
curl https://cdn.es.listbase.org/index.json | jq '.datasets[] | select(.category=="food") | .id'

# Fetch a dataset
curl https://cdn.es.listbase.org/food/es-restaurantes-michelin.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/es/food/)
