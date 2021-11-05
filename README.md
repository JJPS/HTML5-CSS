# SUMARIO

- [SUMARIO](#sumario)
- [HTML y CSS](#html-y-css)
- [¿Qué es HTML?](#qué-es-html)
  - [Etiquetas con contenido.](#etiquetas-con-contenido)
  - [Etiquetas sin contenido](#etiquetas-sin-contenido)
  - [Atributos](#atributos)
  - [Tipos de etiquetas](#tipos-de-etiquetas)
  - [Comentarios](#comentarios)
# HTML y CSS

Ejemplos y ejercicios de la UD4 de la asignatura DIW en el curso 21-22.

# ¿Qué es HTML?

Definimos HTML como un lenguaje de marcas o etiquetas pero, ¿qué es eso de una etiqueta? y ¿qué tipos de etiquetas tengo?

Básicamente podemos distinguir entre dos tipos de etiquetas:

- Etiquetas con contenido
- Etiquetas sin contenido

## Etiquetas con contenido.

Son etiquetas que tiene tres partes (por este orden)

- Apertura de la etiqueta
- Contenido de la etiqueta
- Cierre de la etiqueta

Algo así:

```HTML:
<etiqueta>
     Contenido de la etiqueta
</etiqueta>
```

HTML tiene un número limitado de etiquetas y no es necesario conocer todas. Con una lista más o menos pequeña podemos construir la gran mayoría de páginas web. En caso contrario, siempre podemos visitar las referencias.

Un ejemplo de etiqueta de HTML con contenido sería un párrafo:

```HTML
<p>
    HOLA MUNDO
</p>
```
`<p>` Sería la apertura

HOLA MUNDO sería el contenido, en este caso sólo texto aunque podríamos meter muchas cosas “dentro”

`</p>` Sería el cierre de la etiqueta

## Etiquetas sin contenido

Son etiquetas que sólo tienen parte de apertura y carecen de contenido. Pueden estar cerradas o no, aunque yo os recomiendo que se cierren. De esta manera:

```HTML
<etiqueta >
<etiqueta />
```

Un ejemplo de etiqueta HTML sin contenido sería una imagen:

```html
<img ...  />
```

## Atributos

Las etiquetas pueden tener atributos de los que nos interesa saber lo siguiente:

- Proporcionan información adicional sobre la etiqueta.
- Las etiquetas puede tener o no tener atributos e incluso tener más de uno.
- Siempre se añaden en la etiqueta de apertura.
- Hay atributos generales (para todas) o específicos (para algunas).
- Se representan nombre_atributo=”valor_atributo”.

Un ejemplo:

```html
<img src="foto.png"  />
```

## Tipos de etiquetas

Hay muchos tipos de etiquetas pero vamos a centrarnos en las siguientes:

- [Etiquetas de cabecera](Contenido/Cabecera.md)
- [Etiquetas de texto](Contenido/Texto.md)
- [Etiquetas de imágenes, tablas, listas y enlaces](Contenido/Imagenes.md)
- [Etiquetas multimedia](Contenido/Multimedia.md)
- [Etiquetas semánticas](Contenido/Semanticas.md)

## Comentarios

Además de todas estas etiquetas nuestra página web podrá llevar comentarios que son, normalmente, texto descriptivos que no se van a mostrar en nuestra web.

Los comentarios van encerrados en esta estructura `<!-- -->` y un ejemplo sería:

```HTML
<!-- Esto es un comentario en HTML -->
```


