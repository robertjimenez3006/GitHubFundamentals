# Resumen de la práctica GitHub Fundamentals

**Participante:** [@robertjimenez3006](https://github.com/robertjimenez3006)
**Plantilla de origen:** [ps-developers-sandbox/GitHubFundamentals](https://github.com/ps-developers-sandbox/GitHubFundamentals)
**Fechas:** del 10 al 13 de noviembre de 2026
**Modalidad:** individual, sin compañero asignado, y siempre desde la interfaz web de GitHub

**Resultado:** se completaron los 10 laboratorios. Las partes pensadas para hacerse en pareja se adaptaron al trabajo individual, como se explica en la sección [Lo que no se hizo](#lo-que-no-se-hizo-o-se-hizo-distinto).

---

## Lo que se hizo

| Lab | Tema | Estado | Evidencia |
|---|---|---|---|
| 1 | Crear un repo desde plantilla | ✅ | Este repositorio (público, creado desde la plantilla) |
| 2 | Issues, etiquetas, milestone y plantilla de issue | ✅ | [#8](../../issues/8), [milestone](../../milestone/1), [plantilla](.github/ISSUE_TEMPLATE/bug_report_robertjimenez3006.md), [#18](../../issues/18) |
| 3 | Discussions | ✅ | [Pregunta Q&A #20](../../discussions/20), [encuesta #24](../../discussions/24) |
| 4 | GitHub Pages | ✅ | <https://robertjimenez3006.github.io/GitHubFundamentals/> |
| 5 | Wiki | ✅ | [Home](../../wiki), [Octocat Table 🐱](../../wiki/Octocat-Table-🐱) |
| 6 | GitHub Projects | ✅ | Proyecto *🏆 Team backlog* (privado, ver la nota del Lab 6) |
| 7 | Proponer cambios con un pull request | ✅ | [PR #25](../../pull/25) |
| 8 | Hacer sugerencias | ✅ | [Sugerencias en el PR #25](../../pull/25/files) |
| 9 | Aplicar sugerencias | ✅ | Commit `bf5d869` *Apply suggestions from code review* |
| 10 | Revisión y merge | ✅ (adaptado) | PR #25 fusionado (commit `8955b5a`) y rama borrada automáticamente |

### Detalle por laboratorio

**Lab 1. Repositorio**
- Creado con *Use this template* como repositorio público, para que Pages y Wiki funcionen con una cuenta gratuita.
- Al crearse, el workflow `Init` abrió solo los issues #1 a #7 (preguntas y retrospectivas del curso).

**Lab 2. Issues**
- Jerarquía de tres niveles con *sub-issues*:
  ```
  #8 🏆 Awesome and epic initiative            [epic]
  ├── #9  🎸 A feature … that rocks           [Feature]
  │   ├── #15 👥 User Story          (cerrada) [User Story]
  │   ├── #16 ❤️ Things users ❤️               [User Story]
  │   └── #17 💯 Crazy feature                 [User Story]
  ├── #10 ⚡ Another epic feature              [Feature]
  └── #11 🔥 Hot feature                       [Feature]
  ```
- Todos los issues están asignados al participante.
- El milestone **Backlog robertjimenez3006** no tiene fecha y contiene las 3 user stories: 1 de 3 cerrada, un 33 %.
- La plantilla `bug_report_robertjimenez3006.md` rellena el título `[Bug]:`, la etiqueta `bug` y el asignado. Se probó creando el issue #18.

**Lab 3. Discussions**
- Se activaron las Discussions en el repositorio.
- Se hizo una pregunta Q&A en Markdown, se le dieron 2 respuestas y se marcó una como respuesta aceptada.
- Se creó una encuesta de películas y se votó en ella.

**Lab 4. GitHub Pages**
- Se publica desde `main` en la carpeta `/docs` (Jekyll y reveal.js).
- El despliegue se comprobó en Actions (`pages-build-deployment`) y se enlazó la web en el *About* del repositorio.

**Lab 5. Wiki**
- Página *Home* con imagen.
- Página *Octocat Table 🐱* con una tabla de 3×3 imágenes.

**Lab 6. Projects** (proyecto *🏆 Team backlog*)
- Contiene 8 elementos: el Epic, los 3 Features, las 3 Stories y el bug.
- Se añadieron las columnas *Labels* y *Milestone*.
- *Status* se renombró a `Todo ✍️`, `In Progress 🚧` y `Done ✅`.
- Campos propios:
  - **Level**, de selección única: Epic 🚀, Feature 🔥, Story 🗣 y Task 🔨.
  - **Quarter 📆**, de iteraciones de 12 semanas desde el 1 de octubre de 2026.
  - **Effort 🔨**, numérico.
- Vistas:
  - **🗒 Backlog**: tabla agrupada por Level.
  - **🗣 Story Board**: tablero filtrado con `level:"Story 🗣"`.
  - **Planning**: tablero con columnas por Quarter y suma de Effort (Q1 = 16, Q2 = 21).
- Nota: el proyecto es **privado**, la visibilidad por defecto, así que su enlace solo funciona para su propietario.

**Lab 7. Pull request**
- Se creó `docs/_slides/robertjimenez3006.md` desde el editor web y se guardó en la rama nueva `robertjimenez3006-slide`.
- Se abrió el PR #25 **en borrador** y se asignó al participante.
- Se dejó un comentario en la línea 6 con una mención `@`.

**Lab 8. Sugerencias**
- Una sugerencia como respuesta al comentario de la línea 6, para cambiar el saludo.
- Otra sugerencia sobre la imagen, en la línea 8, para cambiar el dinotocat por el nyantocat.

**Lab 9. Aplicar sugerencias**
- Las 2 sugerencias se aplicaron **en lote**, en un único commit.

**Lab 10. Revisión y merge**
- El PR #25 se pasó de borrador a *Ready for review*.
- Se activó *Automatically delete head branches* en los ajustes del repositorio.
- Se hizo el merge con *merge commit*, la rama se borró sola y se vio la opción *Restore branch*.
- La diapositiva se comprobó publicada en Pages.

---

## Lo que no se hizo, o se hizo distinto

### No se pudo hacer por trabajar sin compañero

| Lab | Parte del guion | Motivo |
|---|---|---|
| 3 | Responder preguntas y votar encuestas de otros participantes | No hay otros participantes en el repositorio. Las respuestas se escribieron en la propia pregunta. |
| 7 | Mencionar al compañero asignado en el issue #1 | No hay pareja asignada. La mención se hizo al propio usuario, que no genera notificación. |
| 8 | Sugerir cambios en el PR **de otra persona** | Las sugerencias se hicieron sobre el PR propio. |
| 9 | Ver al compañero como **co-autor** del commit | Todas las sugerencias son del mismo autor, así que no aparece ningún co-autor. |
| 9 | Ver al compañero asignado automáticamente como revisor | No hay compañero. |
| 10 | Revisar el PR de un compañero con *Start a review* y aprobarlo | No hay PR ajeno que revisar. GitHub tampoco permite aprobar el PR propio, así que en el PR propio solo se puede enviar una revisión de tipo *Comment*. |
| 10 | **Auto-merge** | El repositorio no tiene una regla que exija aprobación, y aunque la tuviera el PR no podría aprobarse a sí mismo. El merge se hizo a mano. |

### Opcionales que no se hicieron

- **Lab 2:** plantilla de issue personalizada en YAML y `config.yml` para desactivar los issues en blanco.
- **Lab 5:** barra lateral (*sidebar*) de la Wiki.
- **Lab 6:** gráfico en *Insights*, revisión de los *workflows* del proyecto y convertir un *draft issue* en issue.

### Diferencias con el guion por cambios en GitHub

- **Lab 2:** el guion convierte las tareas de una lista en issues (*Convert to issue*). Hoy GitHub lo hace con **sub-issues**, y esa fue la vía usada. Por el camino se crearon por error 3 issues duplicados (#12, #13 y #14); se cerraron como *not planned* y se desvincularon de la jerarquía.
- **Lab 6:** el campo **Level** quedó creado como *Issue field*, un tipo más reciente cuyo valor se guarda en el propio issue y no solo en el tablero. Funciona igual para agrupar y filtrar. Un primer intento de **Quarter** se creó como tipo fecha; se eliminó y se volvió a crear como *Iteration*.

### Pendientes de limpieza (opcionales)

- El issue de prueba [#18](../../issues/18) `[Bug]:` sigue abierto.
- Los issues #1 a #7 del curso siguen abiertos, como en el guion original.
