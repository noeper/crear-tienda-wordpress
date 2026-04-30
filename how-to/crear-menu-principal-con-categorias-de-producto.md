# How-to: crear el menú principal con categorías de producto

## Objetivo

Crear el `Primary Menu` en Astra y añadir en él categorías de producto de WooCommerce.

## Requisitos previos

- Tener instalado y activado el tema Astra.
- Tener instalado y activado WooCommerce.
- Tener creadas las categorías de producto que se van a añadir al menú.

## Qué opción se recomienda usar

El menú puede crearse desde dos zonas de WordPress:

- `Escritorio -> Apariencia -> Menús`
- `Escritorio -> Personalizar -> Menús`

Aunque ambas permiten crear menús, en este caso se recomienda usar la segunda opción.

### Motivo

Desde `Apariencia -> Menús` se pueden añadir categorías de entradas de WordPress, pero no resulta adecuada aquí para trabajar con las categorías de producto de WooCommerce.

Por eso, para este caso, se recomienda crear el menú desde:

`Escritorio -> Personalizar -> Menús`

## Pasos

1. Ve a `Escritorio de WordPress -> Personalizar`.
2. Se abrirá una nueva ventana del personalizador.
3. En esa ventana, entra en `Menús`.
4. Pulsa `Crea un nuevo menú`.
5. Escribe el nombre del menú.
6. Selecciona la ubicación `Primary Menu`.
7. Pulsa `Siguiente` o continúa con la creación del menú.
8. Pulsa `+ Añadir elemento`.
9. En el panel lateral derecho, localiza la opción `Product categories`.
10. Haz clic en cada categoría de producto que quieras añadir.
11. Comprueba que las categorías se van incorporando al menú en la parte derecha.

## Crear subopciones dentro del menú

Si quieres que una categoría quede dentro de otra:

1. Mantén pulsado el elemento del menú.
2. Muévelo ligeramente hacia la derecha.
3. Suéltalo cuando quede anidado bajo la categoría principal.

## Importante

No hay que confundir:
- `Categorías`, que son categorías de entradas de WordPress
- `Product categories`, que son categorías de producto de WooCommerce

En este menú se usarán `Product categories`.

Para una descripción más completa de esta pantalla y de los tipos de elementos disponibles, consulta:
- `reference/pantalla-menus-en-el-personalizador.md`
- `reference/tipos-de-menu-en-astra.md`

## Resultado esperado

El sitio queda con un `Primary Menu` en la parte superior y con enlaces a las categorías de producto seleccionadas.
