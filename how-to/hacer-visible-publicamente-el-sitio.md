# How-to: hacer visible públicamente el sitio

## Objetivo

Quitar la pantalla inicial de `Coming soon` y hacer que el sitio web muestre su página de inicio al escribir la URL pública.

## Contexto

Al principio, el sitio no está accesible públicamente como una tienda normal.

Lo que se muestra es una página con fondo violeta con un mensaje parecido a:

- `Pardon our dust! We're working on something amazing — check back soon!`

También aparece un botón `Acceder`, que lleva a la página de login de WordPress.

## Qué ocurre mientras está así

Mientras esta opción siga activa:
- los visitantes no ven la portada real del sitio
- la URL pública no muestra la página `Home`
- el sitio queda oculto detrás de la pantalla de `Coming soon`

## Ruta

`Escritorio de WordPress -> WooCommerce -> Settings -> Site visibility`

## Pasos

1. Ve a `WooCommerce -> Settings`.
2. Entra en la pestaña `Site visibility`.
3. En esa pantalla verás varias opciones de visibilidad, entre ellas:
   - `Coming soon`
   - `Apply to store pages only`
   - `Share your site with a private link`
   - `Live`
4. Selecciona la opción `Live`.
5. Pulsa el botón `Save changes`.

## Resultado esperado

Después de guardar:
- el sitio deja de mostrar la pantalla violeta de `Coming soon`
- la URL pública del sitio puede mostrar la página de inicio real
- los visitantes ya pueden ver el sitio normalmente
