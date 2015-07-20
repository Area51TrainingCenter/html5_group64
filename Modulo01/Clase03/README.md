# HTML5 Grupo 64

## Modulo 01 - HTML5

### HTML - Clase 03

#### Estructuras HTML

Las estructuras HTML son un conjunto de etiquetas que buscan definir un esqueleto para las páginas web, en principio las páginas se basan en niveles (pisos) y como en la vida misma los niveles SIEMPRE estan uno debajo de otro, para definir estos niveles usaremos la etiqueta `*<div></div>*` sin olvidar darle un nombre al elemento.


```html
<div id="header">
  <h1 class="header-logo">Logo</h1>
  <nav class="main-navigation">
    <ul>
      <li><a href="index.html">Inicio</a></li>
      <li><a href="proyectos.html">Proyectos</a></li>
      <li><a href="contacto.html">Contacto</a></li>
    </ul>
  </nav>
</div>
<div id="content">

</div>
<div id="footer">

</div>
```

La etiqueta `*<div></div>*` es la etiqueta mas usada para la creación de niveles, y en el ejemplo anterior la estamos usando para definir la cabecera, el cuerpo y el pie de la página, sin embargo en HTML5 ya existen etiquetas semanticas para estas 3 partes, las cuales te mostramos a continuación:

```html
<header id="header">

</header>
<section id="content">

</section>
<footer id="footer">

</footer>
```

En principio, aun se puede utilizar `*<div></div>*` para definir estas 3 secciones, pero el uso de etiquetas semánticas define claramente que tipo de contenido tendrá cada nivel.

======
