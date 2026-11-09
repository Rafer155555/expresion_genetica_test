# Metagenómica de suelos y aguas amazónicas afectados por petróleo

**Repositorio didáctico; destinado a practicar organización y control de versiones.**

Caso conceptual de búsqueda de microorganismos amazónicos con posible potencial de degradación de hidrocarburos mediante metagenómica de suelos y aguas afectados por derrames de petróleo. Se desarrolla como actividad grupal de Introducción a la Programación Científica de UNIR.

**No se utilizan datos ni scripts reales.** El repositorio contiene documentación, una plantilla de metadatos sin registros y carpetas ilustrativas. No se han ejecutado análisis ni identificado microorganismos degradantes.

## Propósito y objetivos

Practicar Git y GitHub mediante la creación y organización de un proyecto bioinformático compartido. Los objetivos de esta actividad son:

- Mantener una estructura clara de carpetas y documentar su función.
- Registrar cambios mediante commits descriptivos.
- Colaborar con ramas y solicitudes de cambios (pull requests).
- Distinguir una propuesta científica de resultados obtenidos.

## Contexto del caso conceptual

## Estructura del repositorio

```text
expresion_genetica_test/
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── .gitignore
├── .gitattributes
├── data/
│   ├── README.md
│   ├── raw/README.md
│   └── processed/README.md
├── metadata/
│   ├── README.md
│   ├── muestras_plantilla.csv
│   └── diccionario_muestras.csv
├── docs/
│   ├── README.md
│   └── plan_conceptual.md
├── scripts/
│   └── README.md
└── results/
    ├── README.md
    ├── tables/README.md
    └── figures/README.md
```

| Ruta | Función en el ejemplo |
| --- | --- |
| `data/raw/` | Representar la ubicación de datos originales; solo contiene una explicación. |
| `data/processed/` | Representar la ubicación de datos procesados; solo contiene una explicación. |
| `metadata/` | Mostrar cómo se describirían las muestras mediante una plantilla vacía y su diccionario. |
| `docs/` | Explicar el alcance y las fases del caso conceptual. |
| `scripts/` | Representar la ubicación de programas; no contiene scripts reales. |
| `results/tables/` | Representar la ubicación de tablas; no contiene resultados. |
| `results/figures/` | Representar la ubicación de figuras; no contiene resultados. |

Los archivos README de cada carpeta explican su finalidad y permiten conservar la estructura en Git.

## Licencia

El contenido original del repositorio se distribuye bajo la [licencia MIT](LICENSE).
