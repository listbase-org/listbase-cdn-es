# Tecnología (Technology)

12 datasets — 2,378 records

> Browse at [listbase.org/es/tech/](https://listbase.org/es/tech/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Emojis — nombres en español (CLDR)](es-nombres-de-emoji.json) | 1,966 | 310 KB | [CSV](es-nombres-de-emoji_ES.csv) | [Excel](es-nombres-de-emoji_ES.xlsx) | [View](https://listbase.org/es/tech/es-nombres-de-emoji/) |
| [Husos horarios del mundo (IANA / CLDR en español)](es-husos-horarios.json) | 206 | 37 KB | [CSV](es-husos-horarios_ES.csv) | [Excel](es-husos-horarios_ES.xlsx) | [View](https://listbase.org/es/tech/es-husos-horarios/) |
| [Husos horarios — America (62)](es-husos-horarios-america.json) | 62 | 12 KB | [CSV](es-husos-horarios-america_ES.csv) | [Excel](es-husos-horarios-america_ES.xlsx) | [View](https://listbase.org/es/tech/es-husos-horarios-america/) |
| [Husos horarios — Asia (50)](es-husos-horarios-asia.json) | 50 | 10 KB | [CSV](es-husos-horarios-asia_ES.csv) | [Excel](es-husos-horarios-asia_ES.xlsx) | [View](https://listbase.org/es/tech/es-husos-horarios-asia/) |
| [Husos horarios — Europe (40)](es-husos-horarios-europe.json) | 40 | 8 KB | [CSV](es-husos-horarios-europe_ES.csv) | [Excel](es-husos-horarios-europe_ES.xlsx) | [View](https://listbase.org/es/tech/es-husos-horarios-europe/) |
| [Husos horarios — Africa (23)](es-husos-horarios-africa.json) | 23 | 5 KB | [CSV](es-husos-horarios-africa_ES.csv) | [Excel](es-husos-horarios-africa_ES.xlsx) | [View](https://listbase.org/es/tech/es-husos-horarios-africa/) |
| [Husos horarios — Pacific (12)](es-husos-horarios-pacific.json) | 12 | 3 KB | [CSV](es-husos-horarios-pacific_ES.csv) | [Excel](es-husos-horarios-pacific_ES.xlsx) | [View](https://listbase.org/es/tech/es-husos-horarios-pacific/) |
| [Husos horarios — Atlantic (7)](es-husos-horarios-atlantic.json) | 7 | 3 KB | [CSV](es-husos-horarios-atlantic_ES.csv) | [Excel](es-husos-horarios-atlantic_ES.xlsx) | [View](https://listbase.org/es/tech/es-husos-horarios-atlantic/) |
| [Husos horarios — Indian (6)](es-husos-horarios-indian.json) | 6 | 2 KB | [CSV](es-husos-horarios-indian_ES.csv) | [Excel](es-husos-horarios-indian_ES.xlsx) | [View](https://listbase.org/es/tech/es-husos-horarios-indian/) |
| [Husos horarios — Antarctica (2)](es-husos-horarios-antarctica.json) | 2 | 2 KB | [CSV](es-husos-horarios-antarctica_ES.csv) | [Excel](es-husos-horarios-antarctica_ES.xlsx) | [View](https://listbase.org/es/tech/es-husos-horarios-antarctica/) |
| [Husos horarios — Australia (2)](es-husos-horarios-australia.json) | 2 | 2 KB | [CSV](es-husos-horarios-australia_ES.csv) | [Excel](es-husos-horarios-australia_ES.xlsx) | [View](https://listbase.org/es/tech/es-husos-horarios-australia/) |
| [Husos horarios — Etc (2)](es-husos-horarios-etc.json) | 2 | 2 KB | [CSV](es-husos-horarios-etc_ES.csv) | [Excel](es-husos-horarios-etc_ES.xlsx) | [View](https://listbase.org/es/tech/es-husos-horarios-etc/) |

## Quick Start

```bash
# List all technology datasets
curl https://cdn.es.listbase.org/index.json | jq '.datasets[] | select(.category=="tech") | .id'

# Fetch a dataset
curl https://cdn.es.listbase.org/tech/es-nombres-de-emoji.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/es/tech/)
