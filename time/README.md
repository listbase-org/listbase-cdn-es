# Tiempo y calendario (Time & Calendar)

2 datasets — 96 records

> Browse at [listbase.org/es/time/](https://listbase.org/es/time/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Nombres de meses por calendario (CLDR en español)](es-meses-del-calendario.json) | 74 | 13 KB | [CSV](es-meses-del-calendario_ES.csv) | [Excel](es-meses-del-calendario_ES.xlsx) | [View](https://listbase.org/es/time/es-meses-del-calendario/) |
| [Días, trimestres, periodos del día y eras — nombres en español (CLDR)](es-dias-trimestres-eras.json) | 22 | 5 KB | [CSV](es-dias-trimestres-eras_ES.csv) | [Excel](es-dias-trimestres-eras_ES.xlsx) | [View](https://listbase.org/es/time/es-dias-trimestres-eras/) |

## Quick Start

```bash
# List all time & calendar datasets
curl https://cdn.es.listbase.org/index.json | jq '.datasets[] | select(.category=="time") | .id'

# Fetch a dataset
curl https://cdn.es.listbase.org/time/es-meses-del-calendario.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/es/time/)
