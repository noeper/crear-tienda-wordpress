# Document Maintenance Guide

## Objetivo

Este archivo define reglas editoriales para mantener la documentación de forma consistente y evitar duplicaciones innecesarias.

El objetivo del repositorio es servir como base documental para replicar una tienda online de referencia en WordPress, desplegada en Pantheon y construida con WooCommerce, Astra y Elementor.

No es un inventario de repeticiones. Su función es marcar:
- dónde debe vivir cada tipo de información
- qué archivos son fuente canónica
- qué repeticiones se toleran

## Estructura principal

La organización actual se apoya en Diátaxis:

- `tutorials/` -> recorridos guiados de aprendizaje
- `how-to/` -> tareas concretas
- `reference/` -> pantallas, campos, opciones y listas consultables
- `explanation/` -> conceptos, contexto y relaciones entre ideas

Ya no hay carpetas paralelas antiguas que actúen como fuente viva en paralelo.

La estructura activa del proyecto es la basada en Diátaxis.

La organización por carpetas debe seguir ayudando a una IA o a un alumno a reconstruir la tienda de referencia con el menor ruido posible.

## Fuentes canónicas

### `reference/`

Debe ser la fuente principal para:
- nombres de pantallas
- nombres de botones
- nombres de campos
- opciones disponibles en formularios
- listas de ubicaciones o tipos de menú
- páginas creadas por WooCommerce

Si una lista de opciones ya está en `reference/`, no debe duplicarse entera en `how-to/`.

### `how-to/`

Debe ser la fuente principal para:
- secuencias de pasos
- rutas recomendadas para completar una tarea
- requisitos previos
- resultado esperado

Aquí deben vivir también los pasos operativos ligados al despliegue o configuración en Pantheon cuando formen parte de una tarea concreta.

Puede repetir una navegación mínima si ayuda a ejecutar la tarea, pero no debe convertirse en una copia completa de la referencia de pantalla.

### `explanation/`

Debe ser la fuente principal para:
- definiciones
- comparaciones
- contexto
- razonamiento
- implicaciones

Si un concepto ya tiene archivo propio en `explanation/`, el resto de documentos deberían enlazarlo o resumirlo brevemente, no rehacerlo entero.

### `tutorials/`

Debe usarse para:
- recorridos guiados
- secuencias de aprendizaje para principiantes
- recorridos completos orientados a reconstruir la tienda de referencia de principio a fin

Puede reutilizar pasos de `how-to/`, pero no debe convertirse en una colección de referencias detalladas de interfaz.

## Repeticiones permitidas

Se permiten repeticiones pequeñas cuando mejoran la legibilidad.

Ejemplos aceptables:
- una frase breve para recordar qué hace Astra
- una mención corta a que `Product categories` no es lo mismo que `Categorías`
- una ruta mínima dentro de un `how-to`

## Repeticiones que conviene evitar

Se deben evitar:
- listas largas de campos copiadas entre `reference/` y `how-to/`
- explicaciones conceptuales completas repetidas en varios archivos
- tablas o enumeraciones de opciones repetidas en más de una referencia
- copiar enteras pantallas de interfaz dentro de un procedimiento

## Regla práctica antes de editar

Antes de añadir contenido nuevo, comprobar:

1. si ya existe un archivo que sea la fuente canónica del tema
2. si la información nueva es conceptual, procedimental o de referencia
3. si conviene enlazar un archivo existente en lugar de duplicarlo

## Criterio de granularidad

No dividir por cada frase o botón.

La unidad recomendada es:
- un concepto cohesivo
- una tarea completa
- una pantalla o bloque funcional

## Revisión recomendada

Cuando el repositorio crezca, revisar periódicamente:
- si un `how-to` está absorbiendo demasiada referencia de interfaz
- si un archivo de `explanation/` se ha vuelto demasiado amplio y conviene descomponerlo
- si existen dos archivos que responden a la misma pregunta principal
- si el contenido sigue dejando claro qué parte ayuda a replicar la tienda de referencia y qué papel tiene Pantheon dentro del proceso
