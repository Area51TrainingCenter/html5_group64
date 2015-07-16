# HTML5 Grupo 64

## Modulo 01 - HTML5

### HTML

#### Clase 01 - Etiquetas HTML

Las etiquetas son los elementos básicos de una pagina web, dichas elementos vienen en pares:

```html
<p>Esto es un texto, y esta contenido en una etiqueta HTML.</p>
```

La `<p>` es la apertura de la etiqueta y la `</p>` indica el cierre de la misma, notese que la etiqueta de cierra siempre lleva un "/".

======

#### Clase 01 - Pagina HTML

Las paginas HTML son nada mas y nada menos que un conjunto de etiquetas que finalmente son interpretadas por un navegador web, la estructura basica de una página web se presenta de la siguinte manera:

```html
<!doctype html>
<html>
  <head>
    <meta charset="utf-8" >
    <meta http-equiv="X-UA-Compatible" content="IE=edge" >
    <title>My First Webpage</title>
    <link href="style.css" type="text/css" rel="stylesheet" />
    <script src="app.js" type="text/javascript"></script>
  </head>
  <body>
    <h1>Esto es un Titulo</h1>
    <p>Texto de contenido</p>
  </body>
</html>
```

Inicialmente una página web consta de 2 grandes facciones, la primera es **<head> ... </head>**, en esta gran sección se guardan configuraciones de la página y accesos a recursos externos que la página pueda necesitar *(hoja de estilos, archivos javascript, etc.)* tambien se define el titulo de la pagina usando la siguiente etiqueta **<title> ... </title>**

La segunda gran facción es **<body> </body>** y es en esta facción donde se define todo lo que se verá a traves del navegador web. Esta zona contendrá en principio todos los contenidos *(titulos, textos, listados, imagenes, etc)*

======

#### Clase 01 - Tipos de Etiqueta HTML

En principio existen 2  tipos de etiqueta HTML, la primera es una etiqueta *par* quiero decir que tiene 2 partes, su apertura `<p>` y cierre `</p>`. El segundo tipo de etiqueta es del tipo *individual* `<img />` y como se puede ver no tiene par.

##### Ejemplos:

```html
<!-- Etiqueta par -->
<p>Esto es un texto, y esta contenido en una etiqueta HTML par.</p>

<!-- Etiqueta individual -->
<img />
```

======

#### Clase 01 - Atributos en Etiquetas HTML

Dentro de las etiquetas HTML existe un concepto llamado atributos, que basicamente son parametros adicionales que las etiquetas HTML aceptan para cumplir ciertos propositos o configuraciones.

Estos atributos consta de 2 partes, la primera es el nombre del atributo y la segunda es el valor del atributo, tal como se muestra en el siguiente ejemplo:

```html
<!-- Un solo atributo -->
<p class="texto">Esto es un texto, y esta contenido en una etiqueta HTML par.</p>

<!-- Multiples atributos -->
<img class="foto" src="imagen.jpg" alt="foto de un perro" width="300" height="280" />
```

Se considera como nombre de atributos *class, src, alt, width, y height* y como valores *foto, imagen.jpg, foto de un perro, 300, y 280*, todos los valores de los atributos deben estar entre comillas *"foto de un perro"* y entre el nombre y el valor del atributo debe haber un signo **=**

Una etiqueta HTML puede recibir multiples atributos.

======

### Referencias

[HTML 5 - Primer Contacto](http://slides.com/victor_malca/html-first-contact)
[HTML 5 - Manejo de atributos](http://slides.com/victor_malca/html-using-attributes)
