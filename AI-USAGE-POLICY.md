# AI Usage Policy

## Objetivo

Esta documentación está pensada para utilizarse como fuente principal de verdad al trabajar con herramientas de IA como NotebookLM, ChatGPT u otras similares.

La IA debe ayudar al usuario a replicar la tienda online de referencia basándose prioritariamente en los archivos Markdown y, cuando haga falta, en los recursos multimedia de este repositorio.

La réplica se construye con WordPress, Pantheon, WooCommerce, Astra y Elementor, y la documentación está organizada siguiendo Diátaxis para facilitar ese uso.

## Reglas de uso

1. Usa estos archivos Markdown como fuente principal y prioritaria.
2. Trata esta documentación como información canónica para guiar al alumnado.
3. Usa también los recursos multimedia del repositorio cuando aporten contexto útil para replicar la tienda de referencia.
4. Si la respuesta está contenida en los archivos, responde basándote solo en ellos.
5. Si la información no aparece en los archivos, dilo claramente.
6. Si la herramienta permite consultar otras fuentes, puedes buscar la información fuera de estos archivos.
7. Cuando uses información externa, debes indicarlo de forma explícita en la respuesta.
8. No mezcles información de los Markdown, de los recursos del repositorio y de las fuentes externas sin avisarlo claramente.

## Prioridad de uso del contenido

Cuando el objetivo sea guiar al alumno dentro de este repositorio, la IA debe priorizar:

1. `tutorials/` para acompañar el aprendizaje paso a paso.
2. `how-to/` para ejecutar tareas concretas.
3. `reference/` para resolver dudas sobre pantallas, campos, botones y opciones.
4. `explanation/` para aclarar conceptos y contexto.

## Uso del contenido multimedia

El contenido multimedia no está cargado en NotebookLM por limitaciones de tamaño.

Cuando se quiera consultar, citar o añadir contenido multimedia, la IA debe devolver esta ruta del repositorio:

- `https://github.com/noeper/tutorial-crear-tienda-online/tree/main/assets`

## Cómo debe responder la IA

### Si la respuesta está en los archivos

La IA debe responder basándose en la documentación y en los recursos proporcionados, sin añadir información externa innecesaria.

### Si la respuesta no está en los archivos

La IA debe advertirlo de forma clara antes de responder.

Ejemplos de formulación:

- `Esta respuesta no aparece en los archivos Markdown proporcionados.`
- `La información siguiente no ha sido extraída de la documentación del repositorio, sino de una fuente externa.`
- `Según los archivos proporcionados no dispongo de esa información. Lo siguiente procede de una fuente distinta.`

### Si una respuesta combina ambas fuentes

La IA debe separar claramente:

- qué parte procede de los archivos Markdown o de los recursos del repositorio
- qué parte procede de fuentes externas

Ejemplos de formulación:

- `Según la documentación proporcionada, ...`
- `Lo siguiente no aparece en los archivos y procede de una fuente externa: ...`

## Principio editorial

La prioridad de esta documentación es reducir el ruido y evitar respuestas inventadas o confusas.

Por eso:

- primero se consulta el repositorio
- después, solo si hace falta, se complementa con información externa
- y siempre debe indicarse el origen de esa información
