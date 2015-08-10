# HTML5 Grupo 64

## Modulo 01 - HTML5

### HTML - Clase 05

#### Estructuras HTML (3)

##### Maquetación Landing PRECHU V1

En esta clase veremos como es que crearemos una primera versión de la plantilla HTML, basicamente veremos división de secciones mediante el manejo de etiquetas ``<section>``, ``<header>``, ``<footer>``.

Asimismo veremos como crear subsecciones dentro de cada una de las secciones principales, definiremos una pequeña CSS para visualmente resaltar las zonas creadas para esta plantilla.

###### HTML

```html
<!doctype html>
<html>
    <head>
        <meta charset="utf-8">
        <meta http-equiv="x-ua-compatible" content="ie=edge">
        <title>P&aacute;gina</title>
        <meta name="description" content="">
        <meta name="viewport" content="width=device-width, initial-scale=1">

        <link rel="stylesheet" type="text/css" href="css/main.css">
    </head>
    <body>

        <header class="main-header">
            <h1 class="page-logo">Prechu</h1>

            <nav class="page-navigation">
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="products.html">Products</a></li>
                    <li><a href="services.html">Services</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>
            </nav>
        </header>

        <section class="main-content">
            <div class="sub-content-full">
                <p>Sub Nivel 1</p>
            </div><!-- .sub-content-full -->
            <div class="sub-content">
                <p>Sub Nivel 2</p>
            </div><!-- .sub-content -->
            <div class="sub-content">
                <p>Sub Nivel 3</p>
            </div><!-- .sub-content -->
        </section>

        <footer class="main-footer">
            <p class="copyright">Copyright &copy; 2012-2013 cssauthor.com</p>
        </footer>

    </body>
</html>
```

###### CSS

```css
html,
body
{
    border: 0px;
    margin: 0px;
    padding: 0px;
}

/*
 * HEADER
 */
.main-header
{
    background-color: red;
    display: block;
    margin: 0px auto;
    width: 970px;
}

/*
 * CONTENT
 */
.main-content
{
    background-color: orange;
    display: block;
}

.sub-content-full
{
    background-color: brown;
    display: block;
    width: 100%;
}

.sub-content
{
    background-color: green;
    color: white;
    display: block;
    margin: 0px auto;
    width: 970px;
}

/*
 * FOOTER
 */
.main-footer
{
    background-color: purple;
    display: block;
    margin: 0px auto;
    width: 970px;
}
```
======
