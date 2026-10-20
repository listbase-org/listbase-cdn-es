# Medio ambiente (Environment)

4 datasets — 3,016 records

> Browse at [listbase.org/es/environment/](https://listbase.org/es/environment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Centrales eléctricas de España](es-centrales-electricas.json) | 2,987 | 1517 KB | [CSV](es-centrales-electricas_ES.csv) | [Excel](es-centrales-electricas_ES.xlsx) | [View](https://listbase.org/es/environment/es-centrales-electricas/) |
| [Unidades de medida — categoría 'energy' (14)](es-unidades-de-medida-energy.json) | 14 | 5 KB | [CSV](es-unidades-de-medida-energy_ES.csv) | [Excel](es-unidades-de-medida-energy_ES.xlsx) | [View](https://listbase.org/es/environment/es-unidades-de-medida-energy/) |
| [Centrales nucleares en España](es-centrales-nucleares.json) | 10 | 7 KB | [CSV](es-centrales-nucleares_ES.csv) | [Excel](es-centrales-nucleares_ES.xlsx) | [View](https://listbase.org/es/environment/es-centrales-nucleares/) |
| [Unidades de medida — categoría 'temperature' (5)](es-unidades-de-medida-temperature.json) | 5 | 3 KB | [CSV](es-unidades-de-medida-temperature_ES.csv) | [Excel](es-unidades-de-medida-temperature_ES.xlsx) | [View](https://listbase.org/es/environment/es-unidades-de-medida-temperature/) |

## Quick Start

```bash
# List all environment datasets
curl https://cdn.es.listbase.org/index.json | jq '.datasets[] | select(.category=="environment") | .id'

# Fetch a dataset
curl https://cdn.es.listbase.org/environment/es-centrales-electricas.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/es/environment/)
