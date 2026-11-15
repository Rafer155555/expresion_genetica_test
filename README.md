# Metagenómica de suelos y aguas amazónicas afectados por petróleo

**Repositorio didáctico; destinado a practicar organización y control de versiones.**

Caso conceptual de búsqueda de microorganismos amazónicos con posible potencial de degradación de hidrocarburos mediante metagenómica de suelos y aguas afectadas por derrames de petróleo. Se desarrolla como actividad grupal de Introducción a la Programación Científica de UNIR.

**No se utilizan datos ni scripts reales.** El repositorio contiene documentación, una plantilla de metadatos sin registros y carpetas ilustrativas. No se han ejecutado análisis ni identificado microorganismos degradantes.

## Propósito y objetivos

Practicar Git y GitHub mediante la creación y organización de un proyecto bioinformático compartido. Los objetivos de esta actividad son:

- Mantener una estructura clara de carpetas y documentar su función.
- Registrar cambios mediante commits descriptivos.
- Colaborar con ramas y solicitudes de cambios (pull requests).
- Distinguir una propuesta científica de resultados obtenidos.

## Contexto del caso conceptual

El Ecuador se encuentra entre los 17 países megadiversos del mundo, pese a su extensión de 256,370 Km^2, siendo uno de los que más especies se puede encontrar por kilómetro cuadrado. Como describe un informe de la Unicef (2022), la combinación de factores geográficos y ambientales han dado lugar a una extensa diversidad de ecosistemas y especies repartidas entre sus cuatro regiones, Insular, Litoral, Sierra y Amazonía. 

Dentro de la región Amazónica, lado oriental del país continental, se concentra la mayor actividad pretolera y una de las fuentes de ingresos más fuertes que tiene el Ecuador, siendo cerca del 6 % del PIB (Producto Interno Bruto), lo que trae consigo una contaminación por derrames e infiltraciones de petroleo en las zonas de extracción y refinamiento asi como en los oleoductos y poliductos que están repartidos por las principales provincias. Lo que acarrea problemas de contaminación de cuerpos de agua cercanos, suelos, flora y fauna.

Por ende, en el presente caso se explorará de manera teórica la metagenómica de suelos y cuerpos lacustres afectados por estos problemas, con el fin de recoger datos de bioprospección e identificación de posibles microorganismos que sean capaces de degradar estos compuestos y permitan la creación de planes de biorremediación a largo plazo para estas zonas afectadas. 

## Estructura del repositorio

```text
expresion_genetica_test/
├── README.md
├── LICENSE
├── .gitignore
├── .gitattributes
│
├── data/
│   ├── README.md
│   ├── raw/
│   │   └── README.md
│   └── processed/
│       └── README.md
│
├── metadata/
│   ├── README.md
│   ├── muestras_plantilla.csv
│   └── diccionario_muestras.csv
│
├── docs/
│   ├── README.md
│   └── plan_conceptual.md
│
├── scripts/
│   └── README.md
│
└── results/
    ├── README.md
    │
    ├── tables/
    │   ├── README.md
    │   ├── tabla_microorganismos.csv
    │   ├── tabla_genes.csv
    │   ├── tabla_abundancia.csv
    │   └── tabla_funciones.csv
    │
    ├── figures/
    │   ├── README.md
    │   ├── diversidad_microbiana.png
    │   ├── abundancia_taxonomica.png
    │   ├── genes_biodegradacion.png
    │   ├── rutas_metabolicas.png
    │   └── comparacion_muestras.png
    │
    ├── Interpretacion_datos/
    │   ├── README.md
    │   ├── genes_identificados.csv
    │   ├── interpretacion_biologica.md
    │   └── rutas_metabolicas.csv
    │
    ├── quality_control/
    │   ├── README.md
    │   ├── reporte_fastqc.csv
    │   ├── calidad_secuencias.md
    │   └── resumen_calidad.csv
    │
    └── sequence_cleaning/
        ├── README.md
        ├── resumen_limpieza.csv
        ├── procesamiento_secuencias.md
        └── estadisticas_filtrado.csv
```

## Descripción de las carpetas

| Ruta | Función en el proyecto |
|---|---|
| `data/raw/` | Almacenamiento de secuencias originales. |
| `data/processed/` | Secuencias procesadas y filtradas. |
| `metadata/` | Información y descripción de las muestras. |
| `docs/` | Metodología y documentación conceptual. |
| `scripts/` | Organización de programas y códigos bioinformáticos. |
| `results/tables/` | Tablas de microorganismos, genes y abundancia. |
| `results/figures/` | Gráficos y representaciones visuales. |
| `results/Interpretacion_datos/` | Interpretación biológica de genes y microorganismos. |
| `results/quality_control/` | Reportes de evaluación de calidad de secuencias. |
| `results/sequence_cleaning/` | Resultados de limpieza y filtrado de secuencias. |

**Nota:** Las secuencias, tablas, estadísticas y resultados de este repositorio son simulados y tienen fines didácticos. Los nombres de herramientas representan las propuestas de análisis, no procesos experimentales ejecutados.

Los archivos README de cada carpeta explican su finalidad y permiten conservar la estructura en Git.

## Licencia

El contenido original del repositorio se distribuye bajo la [licencia MIT](LICENSE).
