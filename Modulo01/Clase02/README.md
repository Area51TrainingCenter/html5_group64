# HTML5 Grupo 64

## Modulo 01 - HTML5

### HTML - Clase 02

#### Atributos en Etiquetas HTML

Dentro de las etiquetas HTML existe un concepto llamado atributos, que basicamente son parámetros adicionales que las etiquetas HTML aceptan para cumplir ciertos propositos o configuraciones.

Estos atributos se escriben en minísculas y consta de 2 partes, la primera es el nombre del atributo y la segunda es el valor del atributo, tal como se muestra en el siguiente ejemplo:


```html
<!-- No atributos declarados -->
<p>Esto es un texto, y esta contenido en una etiqueta HTML par.</p>

<!-- Multiples atributos -->
<img src="imagen.jpg" alt="foto de un perro" width="300" height="280" />
```

Se considera como nombre de atributos `*class, src, alt, width, y height*` y como valores `*foto, imagen.jpg, foto de un perro, 300, y 280*`, todos los valores de los atributos deben estar entre comillas *"foto de un perro"* y entre el nombre y el valor del atributo debe haber un signo `**=**`

Una etiqueta HTML puede recibir multiples atributos.

======

#### Manejo de atributos *class* y *id*

Estos atributos son los mas usados en el desarrollo de páginas, y sirve para categorizar y nombrar etiquetas HTML en la página respectivamente.

```html
<!-- Uso de atributo class y id -->
<p id="primer_texto" class="texto">Esto es un texto de relleno para mostrar como se ingresa contenido.</p>
<p id="segundo_texto" class="texto">Esto es un segundo texto, que basicamente busca hacer lo mismo que el texto anterior.</p>
<p class="texto">Esto es un tercer texto que tambien muestra contenido.</p>
<p class="texto">Esto es un cuarto párrafo para completar la idea.</p>

```

El valor del atributo *id* a diferencia del atributo *class* NO puede ni debe repetirse, en el ejemplo anterior se ve que el primer párrafo tiene un *id* diferente al segundo párrafo.

Con respecto al valor del atributo *class* este si puede repetirse consecutivamente de tal manera que varias etiquetas pueden compartir el mismo *class*


### Referencias

[HTML 5 - Manejo de atributos](http://slides.com/victor_malca/html-using-attributes)
