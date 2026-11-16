
# Mapas de calor (Heatmaps)

Esta carpeta contiene los mapas de calor generados a partir de los datos simulados de abundancia microbiana y genes funcionales relacionados potencialmente con la transformación de hidrocarburos.

## Objetivo

Representar visualmente los patrones de abundancia de los microorganismos y genes funcionales entre las muestras analizadas.

## Contenido

Se almacenarán los siguientes resultados:

- `resultados_heatmaps.zip`
- `Mapas de calor.png`

## Metodología

Se utilizarán las abundancias relativas de los microorganismos y genes funcionales. Posteriormente, los valores serán estandarizados mediante puntuaciones Z (Z-score) para facilitar la visualización de los patrones de abundancia.

Se aplicará agrupamiento jerárquico para organizar las muestras y las variables según sus similitudes.

## Interpretación

Los colores permitirán identificar valores de abundancia relativa superiores o inferiores al promedio de cada microorganismo o gen dentro del conjunto analizado.

**Nota:** Los valores representados corresponden a datos simulados y estandarizados. Los colores no representan abundancias absolutas ni actividad metabólica.
