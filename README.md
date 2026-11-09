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

La pregunta orientadora es: ¿cómo se organizaría un proyecto de metagenómica para explorar comunidades microbianas de suelos y aguas amazónicas afectados por petróleo y proponer posibles candidatos asociados con la degradación de hidrocarburos?

El enfoque corresponde a ADN ambiental y potencial funcional. La presencia hipotética de genes relacionados con degradación no demostraría actividad, expresión génica ni degradación efectiva. No se formulan conclusiones biológicas en esta actividad.

El nombre técnico `expresion_genetica_test` se conserva como identificador inicial del repositorio. El caso acordado por el grupo es de metagenómica.

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

## Requisitos e instrucciones de uso

Para consultar el proyecto basta con un navegador. Para practicar localmente se necesita Git, un editor de texto y una terminal Bash en Linux, macOS o Git Bash en Windows.

```bash
git clone https://github.com/Rafer155555/expresion_genetica_test.git
cd expresion_genetica_test
git status
git log --oneline -10
```

1. Leer este documento y el [plan conceptual](docs/plan_conceptual.md).
2. Consultar la [plantilla de metadatos](metadata/muestras_plantilla.csv) y su [diccionario](metadata/diccionario_muestras.csv). La plantilla contiene únicamente encabezados.
3. Realizar una mejora documental en una rama propia siguiendo la [guía de colaboración](CONTRIBUTING.md).
4. Revisar y fusionar las aportaciones acordadas por el grupo.

No hay programas que instalar o ejecutar para realizar un análisis metagenómico en este repositorio.

## Trabajo en grupo

El grupo acordará el reparto de tareas durante la reunión. Las aportaciones se registrarán mediante commits y pull requests de cada integrante. No se atribuyen tareas realizadas a personas que todavía no hayan contribuido.

## Licencia

El contenido original del repositorio se distribuye bajo la [licencia MIT](LICENSE).
