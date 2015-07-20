# HTML5 Grupo 64

## Modulo 01 - HTML5

### HTML - Clase 04

#### Estructuras HTML (2)

##### Manejo de Niveles y Subniveles.

Dentro de lo que son estructuras HTML existe tambien el concepto de subniveles, los cuales son niveles dentro de los niveles, los cuales sirven para separar de manera mas ordenada los contenidos que se ingresaran en el nivel, mira el siguiente ejemplo:

```html
<header id="header">
  <!-- nivel superior -->
  <div class="header-top-level">
    <h1 class="header-logo">Logo</h1>
  </div>

  <!-- nivel inferior -->
  <div class="header-bottom-level">
    <nav class="main-navigation">
      <ul>
        <li><a href="index.html">Inicio</a></li>
        <li><a href="proyectos.html">Proyectos</a></li>
        <li><a href="contacto.html">Contacto</a></li>
      </ul>
    </nav>
  </div>

</header>
<section id="content">

</section>
<footer id="footer">

</footer>
```

======
