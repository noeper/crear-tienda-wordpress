# How-to: crear un sitio WordPress en Pantheon

## Objetivo

Crear un nuevo sitio WordPress en Pantheon y llegar al panel desde el que se puede acceder al sitio y al escritorio de WordPress.

## Requisitos previos

- Tener acceso a una cuenta de Pantheon.
- Estar dentro del dashboard principal de Pantheon.

## Pasos

1. En el panel lateral, entra en `Home`.
2. En la pantalla principal, pulsa el botón `Create New Site`.
3. El foco pasará a `Sites` y se abrirá una pantalla para elegir entre:
   - `WordPress`
   - `Drupal`
   - `Custom Upstream`
4. Selecciona `WordPress`.
5. En la siguiente pantalla, localiza la sección `Where will your code be hosted?`.
6. Debajo verás un bloque con:
   - el logo de Pantheon
   - la palabra `Pantheon`
   - el texto `Host code directly on Pantheon's integrated Git repository`
7. Haz clic en ese bloque.
8. En la ventana que se abre, completa `Name your site*`.
9. En `Choose a Workspace for your site`, selecciona el workspace que corresponda a tu cuenta o deja la opción por defecto si ya aparece una adecuada.
10. En `Choose where site data is stored`, selecciona `European Union`.
11. Pulsa el botón `Create site`.
12. Aparecerá una ventana de confirmación. Pulsa `Confirm`.

## Confirmación del workspace

En esta fase puede aparecer un mensaje como este:

- `Confirm workspace`
- `You're creating this site in the [nombre de tu workspace] workspace. This choice might affect costs.`

Después de confirmar, se abrirá una ventana con una barra de progreso.

También puede aparecer este aviso:

- `Information: Keep this tab open while site creation is in progress.`

## Tiempo de espera

La creación del sitio tarda unos minutos.

Según tu experiencia, el proceso suele tardar entre 4 y 5 minutos.

Mientras tanto:
- la barra de progreso irá avanzando
- conviene no cerrar la pestaña

## Final del despliegue

Cuando termina, aparece una pantalla con:
- el mensaje `WordPress deployment complete`
- la barra de progreso en verde
- algunas sugerencias para empezar

En ese momento, pulsa el botón `Go site dashboard`.

## Llegada al dashboard del sitio

Al entrar en el dashboard del sitio verás varias pestañas:
- `Multidev`
- `Dev`
- `Test`
- `Live`

Por defecto, el foco suele estar en `Dev`.

Dentro de esa pestaña aparecen dos botones importantes:
- `Dev site`
- `Dev admin`

## Diferencia entre Dev site y Dev admin

### Dev site

Lleva al sitio web publicado en el entorno de desarrollo.

Ejemplo de formato:
- `https://dev-tutienda.pantheonsite.io/`

### Dev admin

Lleva al escritorio de administración de WordPress.

Ejemplo de formato:
- `https://dev-tutienda.pantheonsite.io/wp-admin/`

## Qué hacer a continuación

Para empezar con la configuración inicial de WordPress, debes entrar en `Dev admin`.

La instalación o configuración inicial de WordPress se explicará en otro fichero.

## Resultado esperado

El sitio queda creado en Pantheon y ya puedes acceder:
- al frontend con `Dev site`
- al escritorio de WordPress con `Dev admin`
