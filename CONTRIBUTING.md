# Colaboración en el repositorio didáctico

Repositorio didáctico; destinado a practicar organización y control de versiones. Las aportaciones consisten en documentación y organización. No se incorporan datos ni scripts reales.

## Preparar una aportación

Aceptar la invitación de GitHub, clonar el repositorio y configurar el nombre y correo propios dentro de la copia local:

```bash
git config user.name "Nombre Apellido"
git config user.email "correo asociado a tu cuenta de GitHub"
```

Antes de iniciar un cambio, comprobar con `git status` que no hay trabajo pendiente de guardar. Después:

```bash
git switch main
git pull --ff-only origin main
git switch -c docs/descripcion-del-cambio
```

Elegir un nombre de rama distinto para cada aportación. Editar los archivos acordados y revisar los cambios:

```bash
git status
git diff
```

Añadir solamente los archivos modificados para esa aportación. Ejemplo para una mejora del plan conceptual:

```bash
git add docs/plan_conceptual.md
git diff --staged
git commit -m "Aclarar alcance didactico del plan conceptual"
git push -u origin docs/descripcion-del-cambio
```

## Revisar e integrar

1. Abrir una pull request hacia `main` y explicar qué se cambió y por qué.
2. Pedir a otro integrante que compruebe la claridad del contenido y los enlaces.
3. Resolver las observaciones y fusionar cuando el grupo esté conforme.
4. Actualizar la copia local con `git switch main` y `git pull --ff-only origin main`.

Este es el procedimiento de trabajo acordable por el grupo; no implica que existan reglas automáticas de protección de ramas.

## Convenciones

- Usar nombres de archivos breves, sin espacios ni tildes, y rutas relativas en enlaces internos.
- Conservar el texto del alcance didáctico en el README principal.
- Registrar cambios coherentes con mensajes específicos, por ejemplo `Explicar funcion de carpetas de resultados`.
- No presentar carpetas o plantillas como evidencia de análisis ejecutados.
- Revisar `git status` antes de cada commit y comprobar los cambios publicados en GitHub.
