# Modelo básico de e-commerce en WooCommerce

## Producto

Un producto es cualquier elemento que se vende en una tienda online.

Ejemplos:
- Camisa
- Pantalón
- Falda

Cada producto puede tener:
- nombre
- precio
- imagen
- categoría
- etiquetas
- atributos

## Tipos de producto

WooCommerce permite varios tipos de producto, pero en este material se trabaja con:
- producto simple
- producto variable

### Producto simple

Es un producto sin variaciones.

Ejemplo:
- Camisa blanca talla única

Tiene un único precio y una única configuración.

### Producto variable

Es un producto con distintas versiones o variaciones.

Ejemplo:
- Camiseta con talla S, M y L
- Camiseta con color rojo y azul

Cada combinación puede tener:
- precio propio
- stock propio
- imagen propia

## Taxonomías de producto

En WooCommerce, las categorías, etiquetas y marcas sirven para clasificar productos. Los atributos describen características del producto.

### Categorías

Las categorías organizan los productos en grupos.

Ejemplo:
- Hombre -> Camisas
- Mujer -> Faldas

Características:
- Son jerárquicas.
- Organizan la navegación principal de la tienda.
- En este curso, cada producto tendrá una única categoría principal.

### Etiquetas

Las etiquetas agrupan productos de forma flexible.

Ejemplos:
- verano
- casual
- oferta

Características:
- No son jerárquicas.
- Se usan para navegación, búsqueda y SEO.
- Un producto puede tener varias.

### Marcas

Las marcas identifican al fabricante o línea comercial del producto.

Ejemplos:
- Nike
- Zara
- Levi's

Características:
- Son una taxonomía distinta de las categorías.
- Pueden ser jerárquicas.
- Se usan sobre todo para filtrar productos.

### Diferencia entre categorías, etiquetas y marcas

- Las categorías organizan la tienda.
- Las etiquetas agrupan productos por uso, contexto o estilo.
- Las marcas indican quién fabrica el producto.

## Atributos

Los atributos describen características específicas del producto.

Ejemplos:
- talla
- color
- material
- tipo de tejido

### Tipos de atributos

#### Atributos globales

Se crean una vez y se reutilizan en varios productos.

Ejemplos:
- Talla con valores S, M y L
- Color con valores azul, verde, amarillo y rojo

Sirven para mantener coherencia en toda la tienda.

#### Atributos personalizados

Se crean dentro de un producto concreto.

Se usan cuando:
- solo aplican a ese producto
- no tiene sentido añadirlos al sistema general

Ejemplo:
- Tipo de estampado con el valor "Edición limitada 2024"

## Relación entre atributos y productos variables

Los atributos pueden usarse para crear variaciones.

En un producto variable:
- el usuario debe seleccionar los atributos necesarios antes de comprar
- WooCommerce necesita saber qué combinación exacta se está comprando

No todos los atributos generan variaciones.

Ejemplo:
- Material: algodón
- Tipo de tejido: denim

En esos casos:
- el usuario no elige nada
- solo se muestra información adicional

## Diferencia entre etiquetas y atributos

- Las etiquetas agrupan productos.
- Los atributos describen características del producto.
- Las etiquetas se usan para navegación y SEO.
- Los atributos pueden usarse para variaciones o como información.
