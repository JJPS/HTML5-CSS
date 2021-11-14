# CABECERA

- [CABECERA](#cabecera)
- [La etiqueta META](#la-etiqueta-meta)

La cabecera de mi página web es lo que está dentro de la etiqueta y en relación a ella es importante saber lo siguiente:

- Todo lo que va dentro de esa etiqueta no representa contenido alguno, es decir, nada de lo que yo pongo se va a ver en nuestro navegador.
- Contiene otras etiquetas que nos van a ayudar a dar una descripción de mi página.
- Puede contener enlaces a hojas de estilos y scripts.

De las etiquetas que puede contener la cabecera destacaremos las siguientes:

- title: que nos sirve para indicar el título de la página que es lo que se muestra en la parte de arriba del navegador.
- style: que es una etiqueta que me permite incluir estilos.
- meta: que es una etiqueta que puede aparecer varias veces y con distintos atributos y que nos va a servir para dar una descripción de la página de diversas formas y maneras.
- link: para enlazar con archivos externos, normalmente hojas de estilos.
- base: para indicar la ruta base para contruir el resto de las rutas a archivos en mi página web.
- script: para incluir normalmente ficheros javascript que doten de vida o animación a mi web.

# La etiqueta META

Es una etiqueta muy importante ya que, aunque no muestre nada, describe mi web y es, entre otras cosas, lo primero que leen tanto los navegadores como los buscadores.

Puede contener diversos atritutos:

- `<meta charset="utf-8">` Es lo que pondremos siempre para no tener problemas con caracteres “extraños” (acentos, ñ etc…) u otros tipos de alfabetos.
- `<meta name="description" content="......">` Es lo que incluiremos para añadir una descripción sobre lo que es mi web. Ese texto descriptivo irá en en el atributo content.
- `<meta name="keywords" content="...">` Es lo que incluiremos para categorizar el contenidos de mi web. Por ejemplo: 

```html
<meta name="keywords" content="programacion,html,meta">

<meta name="author" content="JaviEPDI">
```
Este descriptor se ha incluido en HTML5, y que hará que mi web se escalará para adaptarse a la pantalla del dispositivo. Esto, no obstante no asegura que se vea bien.

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

Para mostrar actualizaciones de la página cada X segundos. Puede ser interesante para actualizaciones automaticas en páginas que cambian , por ejemplo, las de resultados deportivos.

```html
<meta http-equiv="refresh" content="X"> 
```