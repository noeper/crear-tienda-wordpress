# Cómo funciona WordPress

## Qué es WordPress

WordPress es un sistema de gestión de contenidos (CMS) de software libre y de código abierto.

Permite crear, administrar y diseñar sitios web sin necesidad de programar desde cero, apoyándose en:
- contenido
- temas
- plugins

Según W3Techs, a 11 de abril de 2026 WordPress estaba presente en el 42,5% de todos los sitios web detectados y en el 59,8% de los sitios cuyo CMS se conoce.

## Idea general de funcionamiento

WordPress parte de una base común y después se amplía.

Su lógica general es esta:
- WordPress gestiona el contenido y la administración básica del sitio.
- El tema define gran parte de la apariencia y la estructura visual.
- Los plugins añaden funcionalidades nuevas.

Eso hace que un mismo WordPress pueda evolucionar desde una instalación muy básica hasta una web mucho más compleja, como una tienda online.

## Qué permite hacer una instalación básica

Cuando WordPress se instala por primera vez, ofrece un conjunto básico de funciones de publicación y gestión de contenido.

No es correcto decir que "solo sirve para crear un blog", porque desde el principio también permite crear páginas estáticas. Pero sí es cierto que su modelo inicial está muy marcado por su origen como plataforma de publicación y blogging.

Por eso, al empezar, las dos piezas principales de contenido son las páginas y las entradas.

Para el detalle de esta diferencia, consulta:
- `explanation/paginas-y-entradas-en-wordpress.md`

## Organización básica del contenido

Además de crear páginas y entradas, WordPress permite organizar las entradas mediante categorías y etiquetas.

Para el detalle de cómo funciona esa clasificación, consulta:
- `explanation/categorias-y-etiquetas-en-wordpress.md`

## Relación con WooCommerce

Cuando instalas WooCommerce, aparecen también categorías y etiquetas para productos.

La lógica conceptual es parecida a la de las entradas, pero no son exactamente las mismas taxonomías ni están en el mismo lugar del panel.

Además, WooCommerce añade páginas y configuraciones específicas de tienda.

Para ver las páginas por defecto que introduce, consulta:
- `reference/paginas-creadas-por-woocommerce.md`

## Por qué WordPress suele ampliarse con temas y plugins

Una instalación básica de WordPress suele quedarse corta en cuanto un proyecto crece.

Esto ocurre porque muchos sitios necesitan:
- una apariencia más profesional
- estructuras visuales más avanzadas
- componentes adicionales
- funciones específicas
- una tienda online

Para cubrir esas necesidades se recurre a:
- temas
- plugins

Por eso, para convertir WordPress en una tienda online, no basta con el núcleo base: hace falta instalar un plugin como WooCommerce.

Para profundizar en estas piezas, consulta:
- `explanation/temas-en-wordpress.md`
- `explanation/plugins-en-wordpress.md`

## Qué sensación produce al principio

Una experiencia muy habitual al empezar con WordPress es notar que, al instalar temas y plugins, aparecen opciones nuevas en el escritorio que antes no existían.

Eso puede generar desconcierto porque:
- cambia la interfaz
- aparecen menús nuevos
- algunas funciones se duplican
- a veces hay más de una forma de hacer lo mismo

Por ejemplo, al cambiar de tema pueden modificarse opciones dentro de `Apariencia`, y al instalar WooCommerce aparecen nuevas pantallas, ajustes, páginas y taxonomías específicas.

## Ejemplo: qué ocurre al instalar un tema como Astra

Otra fuente de cambio es la instalación de un tema.

Tu percepción aquí es razonable: cuando se activa un tema como Astra, cambian opciones del área `Apariencia` y la experiencia administrativa deja de ser exactamente la misma que tenía WordPress antes.

Eso no significa necesariamente que todo sea "nuevo" en sentido profundo, pero sí que el usuario percibe que la interfaz se reorganiza, se amplía o expone funciones distintas.

## Fortaleza y debilidad del modelo open source

Una de las mayores fortalezas de WordPress es precisamente ser open source.

Eso ha permitido:
- una comunidad enorme
- una gran cantidad de temas y plugins
- una enorme capacidad de personalización
- evolución continua durante muchos años

Pero esa misma fortaleza también introduce una debilidad:
- distintas personas y empresas crean extensiones distintas
- cada una añade sus propias pantallas, opciones y lógicas
- el sistema puede crecer de forma desigual

Por eso, desde la experiencia de usuario, WordPress puede dar a veces una sensación de "Frankenstein":
- muy potente
- muy extensible
- muy respaldado por la comunidad
- pero también áspero en usabilidad y a veces confuso

En resumen:
- su grandeza está en la libertad y la personalización
- su dificultad está en que esa misma apertura produce complejidad

## Sobre el origen bloguero de WordPress

Tu intuición aquí va bien orientada.

WordPress nació en 2003 como una continuación de b2/cafelog, con un enfoque muy ligado a la publicación personal y al blogging.

Por eso muchas de sus estructuras clásicas siguen teniendo una lógica editorial fuerte:
- entradas
- fechas
- categorías
- etiquetas
- archivos

Con el tiempo, WordPress ha evolucionado mucho más allá de ese origen, pero esa herencia sigue notándose.

## Idea clave

WordPress funciona como una base de publicación y gestión de contenido sobre la que se van añadiendo capas.

Esa arquitectura le da dos rasgos a la vez:
- una capacidad enorme de adaptación
- una complejidad creciente a medida que se instalan temas y plugins
