# datos/

Esta carpeta contiene todos los datasets del proyecto GreenByte.

## datos_crudos/

CSVs exportados directamente desde Google Earth Engine, sin modificar.
Nomenclatura: `greenbyte_{TAREA}_{AÑO}.csv`

| Tarea | Variables | Años |
|-------|-----------|------|
| `greenbyte_A_YYYY.csv` | sst, chlor_a, t2m_anomaly, loss_anual, loss_acum, treecover2000, gHM, fire_count | 2015–2024 |
| `greenbyte_B1_YYYY.csv` | NDVI, EVI, LST_day, ET | 2015–2024 |
| `greenbyte_B2_YYYY.csv` | precipitation, precip_anomaly, precip_extreme_days | 2015–2024 |
| `greenbyte_C_YYYY.csv` | NO2, CO, SO2, *_source | 2018–2024 (null para 2015–2017) |

> Los archivos crudos no están incluidos en el repositorio por su tamaño (~40 CSVs).
> Ver instrucciones de reproducción en el README principal para generarlos.

## datos_procesados/

Datasets consolidados y derivados, listos para el tablero.

| Archivo | Descripción |
|---------|-------------|
| `master_greenbyte_v4.csv` | Dataset completo 2015–2024, 26 variables, malla 25 km |
| `master_greenbyte_v4_2019_2024.csv` | Ventana analítica armonizada (solo gases S5P) |
| `master_greenbyte_v4_hotspots.csv` | Dataset 2023 con Gi* y columna `hotspot_gi` |
| `sst_descomposicion_enso.csv` | SST observada + ONI + sst_residual (sin señal ENSO) |
| `tendencias_nacionales_v3.csv` | Promedios anuales nacionales por variable |
| `mann_kendall_tendencias_v3.csv` | Resultados Mann-Kendall + Sen's slope por variable |
| `datos_2023_clusters_hotspots_v3.csv` | Snapshot 2023 con clusters K-Means y hotspots Gi* |
