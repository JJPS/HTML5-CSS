# TEXTO

- [TEXTO](#texto)
  - [Encabezados](#encabezados)
  - [Etiquetas de formato](#etiquetas-de-formato)
  - [Otras etiquetas](#otras-etiquetas)

Hay muchas etiquetas para añadir texto. Vamos a presentarlas siguiendo la siguiente clasificación:

- Encabezados
- Etiquetas de formato
- Otras etiquetas 

## Encabezados

Son etiquetas que nos van a permitir añadir “títulos” o encabezados a distintas secciones de nuestra página. Estas etiquetas tienen el siguiente formato:

```html
 <hx>
     ...
     Contenido o texto
     ...
 </hx>
 ```

x deberá ser sustituido por un número del 1 al 6, desde 1 que es el mayor tamaño hasta 6 que es el más pequeño. El texto se mostrará en negrita.

Veámos un ejemplo simple:

```html
   <h1>Hola</h1>
   <h2>Hola</h2>
   <h3>Hola</h3>
   <h4>Hola</h4>
   <h5>Hola</h5>
   <h6>Hola</h6>
```
## Etiquetas de formato

Hay multitud, todas le dan cierto estilo al texto que contienen y destacaremos las siguientes:

- `<b>...</b>` para poner un texto en negrita.
- `<i>...</i>` para poner un texto en cursiva.
- `<del>...</del>` para mostrar un texto tachado.
- `<em>...</em>` para poner un texto con énfasis (similar a cursiva).
- `<sup>...</sup>` para poner un texto como superíndice de otro texto.
- `<sub>...</sub>` para poner un texto como subíndice de otro texto.
- `<mark>...</mark>` para poner un texto subrayado (nuevo en html5).
- `<q>...</q>` para mostrar una pequeña cita.
- `<cite>...</cite>` para mostrar el título de una referencia bibliográfica.
- `<time>...</time>` para mostrar horas.
- `<address>...</address>` para mostrar direcciones
- `<blockquote>...</blockquote>` para poner citas largas.

## Otras etiquetas

- `<br/>` Salto de línea.
- `<p>...</p>` Párrafo.
- `<hr/>` Separación de Tema.
- `<span>..</span>` Contenedor en linea. Aplica estilo al texto o agrupa elementos.