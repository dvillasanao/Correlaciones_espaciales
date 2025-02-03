
<!-- README.md is generated from README.Rmd. Please edit that file -->

## Análisis Espacial de la Marginación Municipal en México (2020)

Este repositorio contiene un análisis espacial utilizando
**correlaciones espaciales** aplicado al **Índice de Marginación 2020**
a nivel municipal, elaborado por el **Consejo Nacional de Población
(CONAPO)**. Se emplean diferentes estadísticos para evaluar la
distribución espacial de la marginación en los municipios de México.

## Contenidos del Repositorio

- **Datos**: Archivos de shapefiles con los municipios de México y el
  Índice de Marginación 2020.
- **Código en R**: Scripts para calcular estadísticos espaciales y
  generar visualizaciones.
- **Resultados**: Mapas y tablas con los principales hallazgos del
  análisis.

## Metodología

Se utilizan los siguientes métodos de análisis espacial:

1.  **Moran’s I Global**: Evalúa la autocorrelación espacial global de
    la marginación.
2.  **Moran Local (LISA)**: Identifica agrupaciones significativas de
    alta y baja marginación.
3.  **Geary’s C**: Mide la heterogeneidad espacial en la distribución
    del índice.
4.  **Getis-Ord Global G**: Determina la concentración espacial de
    valores altos o bajos.

## Requisitos

Para ejecutar los scripts, se necesita tener instalado **R** y las
siguientes librerías:

``` r
install.packages(c("sf", "spdep", "ggplot2", "tidyverse", "tmap"))
```

## Resultados

**Enlace**:

- **Autocorrelación significativa**: La marginación muestra un patrón
  espacial significativo.
- **Clusters de marginación alta y baja**: Se identifican municipios con
  marginación extrema en diferentes regiones del país.
- **Visualización cartográfica**: Mapas que ilustran la distribución de
  la marginación y sus clusters.
