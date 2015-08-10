# HTML5 Grupo 64

## Modulo 01 - HTML5

### HTML - Clase 06

#### Tablas

En esta clase veremos el manejo de la etiqueta ``<table>`` la cual se usa mucho para mostrar matrices de información.

La etiqueta ``<table>`` al igual que las demás etiquetas que hemos visto hasta el momento tambien maneja sus atributos, dicho atributos se muestran a continuación:

```html
<table width="600" border="1" cellspacing="2" cellpadding="1">
  ...
</table>
```

Veremos que los principales atributos de la etiqueta ``<table>`` son

* width="600"
* border="1"
* cellspacing="2"
* cellpadding="1"

El primer atributo controla el ancho de la tabla, su valor se representa como número común y silvestre, por otro lado el segundo atributo controla el grosor del border de la tabla y el valor puede ser 0 o 1 dependiendo de si queremos que se muestre un borde o no, adicional tenemos al tercer atributo que controla el espacio entre celdas y finalmente el cuarto atributo que control el espacio entre el contenido de una celda y la celda misma.

##### Tablas: Secciones

Dentro de las tablas existen 3 secciones principales ``<thead>``, ``<tbody>`` y el ``<tfoot>``, cada una de estas subsecciones mantendra cierto contenido, por ejemplo el ``<thead>`` contendrá los titulos principales de la matriz, por otro lado el ``<tbody>`` podria contener la información detallada de cada titulo y finalmente el ``<tfoot>`` podria contener información adicional menos importante para la matriz.

```html
<table width="600" border="1" cellspacing="2" cellpadding="1">
  <thead>
    ...
  </thead>
  <tbody>
    ...
  </tbody>
  <tfoot>
    ...
  </tfoot>
</table>
```

##### Tablas: Filas y Columnas

Dentro de lo que es estructurar tablas, existen 3 etiquetas importantes a tomar en cuenta en las que finalmente se pondrá el contenido, las etiquetas en mención son: ``<tr>``, ``<th>`` y ``<td>``.

Las etiquetas ``<tr> ... </tr>`` son las etiquetas para definir las filas de una tabla, dicha etiqueta es solo una etiqueta de bloque que no recibe texto.

Las etiquetas ``<th> ... </th>`` y ``<td> ... </td>`` sirven para agregar las columnas a la tabla y son estas etiquetas las que finalmente albergaran los textos y contenidos que aparecerán en la tabla.

```html
<table width="600" border="1" cellspacing="2" cellpadding="1">
  <thead>
    <tr>
      <th>Código</th>
      <th>Titulo del Libro</th>
      <th>Autor del Libro</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>#1923102</td>
      <td>La Ciudad y los Perros</td>
      <td>Mario Vargas Llosa</td>
    </tr>
  </tbody>
</table>
```

En el ejemplo notese que que debe haber la misma cantidad de ``<th></th>`` y ``<td></td>`` para los contenidos, es la mejor manera de mantener integra la tabla.
