# Cultura y religión (Culture & Religion)

2 datasets — 1,065 records

> Browse at [listbase.org/es/culture/](https://listbase.org/es/culture/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Museos en España (Museums in Spain)](es-museos.json) | 1,017 | 218 KB | [CSV](es-museos_ES.csv) | [Excel](es-museos_ES.xlsx) | [View](https://listbase.org/es/culture/es-museos/) |
| [Patrimonio de la Humanidad de la Unesco en España](es-patrimonio-mundial-unesco.json) | 48 | 47 KB | [CSV](es-patrimonio-mundial-unesco_ES.csv) | [Excel](es-patrimonio-mundial-unesco_ES.xlsx) | [View](https://listbase.org/es/culture/es-patrimonio-mundial-unesco/) |

## Quick Start

```bash
# List all culture & religion datasets
curl https://cdn.es.listbase.org/index.json | jq '.datasets[] | select(.category=="culture") | .id'

# Fetch a dataset
curl https://cdn.es.listbase.org/culture/es-museos.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/es/culture/)
