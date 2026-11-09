# Plan conceptual de metagenómica ambiental

**Repositorio didáctico; destinado a practicar organización y control de versiones.** No se utilizan datos ni scripts reales y no se ejecuta este plan.

## Idea científica

Organizar un caso hipotético de estudio de comunidades microbianas de suelos y aguas amazónicas afectados por derrames de petróleo, con interés en posibles candidatos asociados con la degradación de hidrocarburos.

## Fases ilustrativas

| Fase conceptual | Ubicación que la representaría |
| --- | --- |
| Describir ambientes y condiciones de las muestras | `metadata/` |
| Mantener la procedencia de datos originales | `data/raw/` |
| Documentar control de calidad y procesamiento | `data/processed/` y `docs/` |
| Describir perfiles taxonómicos y potencial funcional | `docs/` |
| Organizar tablas y figuras de una interpretación futura | `results/tables/` y `results/figures/` |

El diseño hipotético podría distinguir suelo y agua, así como ambientes afectados y sitios de referencia comparables. Estas categorías no representan muestras recolectadas, accesiones seleccionadas ni datos disponibles.

## Alcance de la interpretación

La metagenómica permite explorar composición taxonómica y potencial funcional a partir de ADN. Una anotación funcional candidata no demuestra expresión, actividad de degradación o eficacia de biorremediación. La vinculación de una función a un microorganismo también requeriría evidencia adecuada.

En esta actividad no se hacen anotaciones, comparaciones, asignaciones funcionales ni validaciones experimentales. Las carpetas de resultados contienen exclusivamente explicaciones de su función.

## Trabajo documental del grupo

1. Revisar el contexto y mantener explícito el alcance didáctico.
2. Explicar la función de cada carpeta y del esquema de metadatos.
3. Registrar mejoras documentales con mensajes de commit descriptivos.
4. Revisar aportaciones mediante pull requests y comprobar la versión final en `main`.

## Referencias de contexto

- [EMBL-EBI sobre metagenómica comparativa](https://www.ebi.ac.uk/training/materials/genome-resolved-metagenomics-bioinformatics-materials/comparative-metagenome-analysis/comparative-metagenome-analysislecture/), para composición y potencial funcional.
- [Tutorial oficial de colaboración en GitHub](https://docs.github.com/en/get-started/using-github/hello-world), para ramas, commits y pull requests.

Estas referencias aportan contexto; no son fuentes de datos utilizados en el ejercicio.
