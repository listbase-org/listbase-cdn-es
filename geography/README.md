# Geografía (Geography)

10 datasets — 129,391 records

> Browse at [listbase.org/es/geography/](https://listbase.org/es/geography/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Es Apellidos Poco Frecuentes](es-apellidos-poco-frecuentes.json) | 48,492 | 6039 KB | [CSV](es-apellidos-poco-frecuentes_ES.csv) | [Excel](es-apellidos-poco-frecuentes_ES.xlsx) | [View](https://listbase.org/es/geography/es-apellidos-poco-frecuentes/) |
| [Es Apellidos Frecuentes](es-apellidos-frecuentes.json) | 25,399 | 3204 KB | [CSV](es-apellidos-frecuentes_ES.csv) | [Excel](es-apellidos-frecuentes_ES.xlsx) | [View](https://listbase.org/es/geography/es-apellidos-frecuentes/) |
| [Es Nombres Mujeres](es-nombres-mujeres.json) | 24,756 | 2127 KB | [CSV](es-nombres-mujeres_ES.csv) | [Excel](es-nombres-mujeres_ES.xlsx) | [View](https://listbase.org/es/geography/es-nombres-mujeres/) |
| [Es Nombres Hombres](es-nombres-hombres.json) | 24,584 | 2114 KB | [CSV](es-nombres-hombres_ES.csv) | [Excel](es-nombres-hombres_ES.xlsx) | [View](https://listbase.org/es/geography/es-nombres-hombres/) |
| [Estaciones de ferrocarril de Espana](es-estaciones-de-ferrocarril.json) | 5,247 | 2113 KB | [CSV](es-estaciones-de-ferrocarril_ES.csv) | [Excel](es-estaciones-de-ferrocarril_ES.xlsx) | [View](https://listbase.org/es/geography/es-estaciones-de-ferrocarril/) |
| [Cascadas y rápidos en España e Hispanoamérica](es-cascadas.json) | 546 | 346 KB | [CSV](es-cascadas_ES.csv) | [Excel](es-cascadas_ES.xlsx) | [View](https://listbase.org/es/geography/es-cascadas/) |
| [Prefijos telefónicos internacionales de países (ITU-T E.164)](es-prefijos-telefonicos-paises.json) | 248 | 97 KB | [CSV](es-prefijos-telefonicos-paises_ES.csv) | [Excel](es-prefijos-telefonicos-paises_ES.xlsx) | [View](https://listbase.org/es/geography/es-prefijos-telefonicos-paises/) |
| [Es Nombres](es-nombres.json) | 60 | 11 KB | [CSV](es-nombres_ES.csv) | [Excel](es-nombres_ES.xlsx) | [View](https://listbase.org/es/geography/es-nombres/) |
| [Es Apellidos](es-apellidos.json) | 40 | 8 KB | [CSV](es-apellidos_ES.csv) | [Excel](es-apellidos_ES.xlsx) | [View](https://listbase.org/es/geography/es-apellidos/) |
| [Población por comunidad autónoma en España (2021) - 19 registros](es-comunidades-poblacion-2021.json) | 19 | 8 KB | [CSV](es-comunidades-poblacion-2021_ES.csv) | [Excel](es-comunidades-poblacion-2021_ES.xlsx) | [View](https://listbase.org/es/geography/es-comunidades-poblacion-2021/) |

## Quick Start

```bash
# List all geography datasets
curl https://cdn.es.listbase.org/index.json | jq '.datasets[] | select(.category=="geography") | .id'

# Fetch a dataset
curl https://cdn.es.listbase.org/geography/es-apellidos-poco-frecuentes.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/es/geography/)
