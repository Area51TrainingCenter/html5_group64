# HTML5 Grupo 64

## Modulo 01 - HTML5

### HTML - Clase 01

#### Etiquetas HTML

Las etiquetas son los elementos básicos de una pagina web, dichas elementos vienen en pares:

```html
<p>Esto es un texto, y esta contenido en una etiqueta HTML.</p>
```

La `<p>` es la apertura de la etiqueta y la `</p>` indica el cierre de la misma, notese que la etiqueta de cierre siempre lleva un "/".

======

#### Clase 01 - Pagina HTML

Las paginas HTML son nada más y nada menos que un conjunto de etiquetas que finalmente son interpretadas por un navegador web, la estructura básica de una página web se presenta de la siguinte manera:

```html
<!doctype html>
<html>
  <head>
    <meta charset="utf-8" >
    <meta http-equiv="X-UA-Compatible" content="IE=edge" >
    <title>Mi primera pagina</title>
    <link href="style.css" type="text/css" rel="stylesheet" />
    <script src="app.js" type="text/javascript"></script>
  </head>
  <body>
    <h1>Esto es un Titulo</h1>
    <p>Texto de contenido</p>
  </body>
</html>
```

Inicialmente una página web consta de 2 grandes facciones, la primera es `<head> </head>`, en esta gran sección se guardan configuraciones de la página y accesos a recursos externos que la página pueda necesitar *(hoja de estilos, archivos javascript, etc.)* tambien se define el titulo de la pagina usando la siguiente etiqueta `<title></title>`

La segunda gran facción es `<body> </body>` y es en esta facción donde se define todo lo que se verá a traves del navegador web. Esta zona contendrá en principio todos los contenidos *(titulos, textos, listados, imagenes, etc)*

======

#### Tipos de Etiqueta HTML

En principio existen 2  tipos de etiqueta HTML, la primera es una etiqueta *par* quiero decir que tiene 2 partes, su apertura `<p>` y cierre `</p>`. El segundo tipo de etiqueta es del tipo *individual* `<img />` y como se puede ver no tiene par.

##### Ejemplos:

```html
<!-- Etiqueta par -->
<p>Esto es un texto, y esta contenido en una etiqueta HTML par.</p>

<!-- Etiqueta individual -->
<img />
```

======

### Referencias

[HTML 5 - Primer Contacto](http://slides.com/victor_malca/html-first-contact)
