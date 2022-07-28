# Markdown

***Markdown*** es un lenguaje simple que se utiliza para crear texto enriquecido (por ejemplo, HTML) con un editor de texto sin formato. Te permite darle un formato básico al texto, utilizando símbolos conocidos y accesibles en todos los teclados. El tamaño de fuente, el color y otras opciones más avanzadas no están disponibles con Markdown.

<br/>

# Índice
- [Markdown](#markdown)
- [Índice](#índice)
  - [Sintaxis Basica](#sintaxis-basica)
    - [Encabezados](#encabezados)
    - [Párrafos](#párrafos)
    - [Saltos de línea](#saltos-de-línea)
    - [Estilos de fuentes](#estilos-de-fuentes)
    - [Bloque de citado](#bloque-de-citado)
    - [Lista desordenada](#lista-desordenada)
    - [Lista ordenada](#lista-ordenada)
    - [Línea horizontal](#línea-horizontal)
    - [Enlaces (Links)](#enlaces-links)
    - [Imagen](#imagen)
    - [Bloque de código](#bloque-de-código)
    - [Carácter de Escape](#carácter-de-escape)
    - [Comentarios](#comentarios)
    - [HTML](#html)
  - [Sintaxis Extendida](#sintaxis-extendida)
    - [Tablas](#tablas)
      - [Alineación](#alineación)
      - [Formateo de texto en tablas](#formateo-de-texto-en-tablas)
    - [Bloques de código cercado](#bloques-de-código-cercado)
      - [Resaltado de sintaxis](#resaltado-de-sintaxis)
    - [Notas de pie de página](#notas-de-pie-de-página)
    - [ID de encabezado](#id-de-encabezado)
      - [Vinculación a ID de encabezado](#vinculación-a-id-de-encabezado)
    - [Listas de definición](#listas-de-definición)
    - [Tachado](#tachado)
    - [Listas de tareas](#listas-de-tareas)
    - [Emojis](#emojis)
    - [Resaltar](#resaltar)
    - [Subíndice](#subíndice)
    - [Superíndice](#superíndice)
    - [Enlace de URL automático](#enlace-de-url-automático)
    - [Deshabilitar vinculación de una URL](#deshabilitar-vinculación-de-una-url)


<br/>
<br/>

## Sintaxis Basica

### Encabezados
Mejores prácticas de encabezado  
Las aplicaciones de Markdown no se ponen de acuerdo sobre cómo manejar un espacio que falta entre los signos de número ( # ) y el nombre del encabezado. Por compatibilidad, siempre ponga un espacio entre los signos numéricos y el nombre del encabezado.

```
# Encabezado 1
## Encabezado 2
### Encabezado 3
#### Encabezado 4
##### Encabezado 5
###### Encabezado 6
```

Otra alternativa para colocar encabezados, aunque de dos niveles, serian dos == para el primer nivel y dos -- para el segundo nivel.


| Markdown                                              | Resultado                |
| ----------------------------------------------------- | ------------------------ |
| Nivel de encabezado 1<br/>  ===============           | <h1>Heading level 1</h1> |
| Nivel de encabezado 2<br/>  ------------------------- | <h2>Heading level 1</h2> |



### Párrafos
Para crear párrafos, use una línea en blanco para separar una o más líneas de texto.

Ejemplo:

Lorem ipsum dolor sit amet, fames ac ante ipsum primis in faucibus. Aenean pulvinar vehicula felis, a suscipit ante interdum quis. Morbi luctus nibh ligula, eget dapibus lacus facilisis sit amet. Proin mollis pretium est vel aliquam. Aenean iaculis consectetur finibus. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Proin in aliquam est. Aenean blandit felis maximus interdum convallis. Donec nec vulputate purus. Sed eleifend dui id pretium consectetur. Fusce imperdiet quam non dapibus lobortis. Praesent dapibus nibh in elit eleifend commodo.

Cras id faucibus nisi, sed gravida leo. Donec et interdum ex, ut vestibulum ipsum. Donec vehicula efficitur pellentesque. Aliquam facilisis lectus nisl. Mauris euismod blandit mi, ultrices feugiat odio varius et. Fusce imperdiet in quam ut bibendum. Nunc nisi lorem, euismod vitae nulla ac, vestibulum pharetra eros.

### Saltos de línea

Para hacer un salto de línea coloque dos espacios al final de la línea o `<br/>`.

Primera línea  
Segunda línea<br/>
Tercera línea  

### Estilos de fuentes

Dar formato al texto en negrita, cursiva y Subrayar.

*Texto en cursiva*  
**Texto en negrita**  
__Texto en negrita__  
***Texto en cursiva y negrita***  
_Texto Subrayado_  

**Lorem ipsum** dolor sit amet, fames ac ante *ipsum* primis in faucibus. Aenean pulvinar vehicula felis, a suscipit ante interdum quis. _Morbi_ luctus nibh ligula, eget dapibus lacus facilisis sit amet. Proin mollis pretium est vel aliquam. Aenean iaculis ***consectetur finibus***. Orci varius <strong>natoque penatibus</strong> et magnis dis <em>parturient montes</em>, nascetur ridiculus mus. Proin in aliquam est. Aenean blandit felis maximus interdum convallis. Donec nec vulputate purus. Sed eleifend dui id pretium consectetur. Fusce imperdiet quam non dapibus lobortis. Praesent dapibus nibh in elit eleifend commodo.

### Bloque de citado

Para crear una cita en bloque, agregue un el signo de mayor que > delante de un párrafo.

>Es en las noches de diciembre, cuando el termómetro está a cero, cuando más pensamos en el sol <P align="right">Los miserables, Victor Hugo<p/>

Bloque de cita anidado:

>**Lorem ipsum** dolor sit amet, fames ac ante *ipsum* primis in faucibus. 
>
>>Aenean pulvinar vehicula felis, a suscipit ante interdum quis. 


### Lista desordenada

Para crear una lista desordenada, agregue guiones ( - ), asteriscos ( * ) o signos más ( + ) delante de las líneas de pedido. Colocar sangria ha uno o más elementos para crear una lista anidada.

- Primer valor
- Segundo valor
- Tercer valor
    - Primer valor nivel 2
      - Primer valor nivel 3
    - Segundo valor nivel 2
- Cuarto valor


Si necesita comenzar un elemento de lista desordenado con un número seguido de un punto, puede usar una barra invertida ( \\ ) para escapar del punto.

- 1968\. A great year!
- I think 1969 was second best.


### Lista ordenada

Para crear una lista ordenada, agregue elementos de línea con números seguidos de puntos. Los números no tienen que estar en orden numérico, pero la lista debe comenzar con el número uno.

1. Primer valor
2. Segundo valor
3. Tercer valor
    1. Primer valor nivel 2
        1. Primer valor nivel 3
        2. Segundo valor nivel 3
    2. Segundo valor nivel 2
4. Cuarto valor

<br/>

Código en HTML:

<ol>
  <li>Primer valor</li>
  <li>Segundo valor</li>
  <li>Tercer valor
    <ol>
      <li>Primer valor nivel 2
          <ol>
            <li>Primer valor nivel 3</li>
            <li>Segundo valor nivel 3</li>
          </ol>
      </li>
      <li>Segundo valor nivel 2</li>
    </ol>
  </li>
  <li>Cuarto valor</li>
</ol>

continue numbered list
Continuar el 

Curiosamente, Markdown no tiene en cuenta el número real. Tanto si escribes tres veces el número uno como si comienzas con el número tres, la lista siempre se iniciará con el número correcto.

### Línea horizontal

Para crear una línea horizontal, use tres o más asteriscos ( *** ), guiones ( --- ) o guiones bajos ( ___ ) en una sola línea.

---


### Enlaces (Links)

Para crear un enlace, encierre el texto del enlace entre corchetes ([Texto a mostrar]) y luego sígalo inmediatamente con la URL entre paréntesis (https://googe.com.do).

Realice busquedas en [Google](https://googe.com.do).

Colocar un título, escríbalo entre comillas después de la URL.

Volver al [`Índice`](#índice).

Realice busquedas en [_**Google**_](https://googe.com.do "Click aquí").

### Imagen

Para agregar una imagen, agregue un signo de exclamación ( ! ), seguido del texto alternativo entre paréntesis y la ruta o URL del recurso de imagen entre paréntesis. Opcionalmente, puede agregar un título entre comillas después de la ruta o URL.

![Markdown](.\markdown-mark-white.svg "Markdown")

![Vivaldi logo](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/175px-Markdown-mark.svg.png)


### Bloque de código

Se utiliza el acento grave para identificar código, y corchetes para identificar el lenguaje de programación.

`Código`  
``Use `code` in your Markdown file.``


### Carácter de Escape

Markdown utiliza ciertos símbolos para el marcado. Si se utilizan, el analizador reaccionará cuando realice la conversión. Son los siguientes:

| Carácter | Descripción                                    |
| -------- | ---------------------------------------------- |
| \        | backslash                                      |
| \`       | backtick (see also escaping backticks in code) |
| *        | asterisk                                       |
| _        | underscore                                     |
| {        | curly braces                                   |
| [        | brackets                                       |
| <        | angle brackets                                 |
| (        | parentheses                                    |
| #        | pound sign                                     |
| +        | plus sign                                      |
| -        | minus sign (hyphen)                            |
| .        | dot                                            |
| !        | exclamation mark                               |
| \|       | pipe (see also escaping pipe in tables)        |

Para utilizar estos caracteres en sentido literal, solo debes insertar una barra invertida delante de cada uno de ellos. Es importante escribir la barra invertida antes de cada carácter, por ejemplo, tanto delante del paréntesis de apertura como del de cierre.

Esto es un \*ejemplo con asteriscos\*.

### Comentarios

Puedes ocultar el contenido del lenguaje de marcado interpretado colocando el contenido en un comentario de HTML `<!-- Comentario... -->`.

<!-- Este contenido no aparecerá en el Markdown renderizado -->

<!---
tu comentario va aqui
y aquí
-->

[comment]: <> (Este contenido no aparecerá en el Markdown renderizado)


### HTML

Muchas aplicaciones de Markdown le permiten usar etiquetas HTML en texto con formato de Markdown. Esto es útil si prefiere ciertas etiquetas HTML a la sintaxis Markdown. Por ejemplo, a algunas personas les resulta más fácil usar etiquetas HTML para imágenes. El uso de HTML también es útil cuando necesita cambiar los atributos de un elemento, como especificar el color del texto o cambiar el ancho de una imagen.  

No puede usar la sintaxis de Markdown dentro de las etiquetas HTML de nivel de bloque. Por ejemplo, `<p>italic and **bold**</p>` no funcionará.

Ejemplo:  
This **word** is bold. This <em>word</em> is italic.

<br/>
<br/>
<br/>

## Sintaxis Extendida

### Tablas

Para agregar una tabla, use tres o más guiones ( --- ) para crear el encabezado de cada columna y use barras verticales ( | ) para separar cada columna. Para compatibilidad, también debe agregar una tubería en cada extremo de la fila.

| Sintaxis   | Descripción |
| ---------- | ----------- |
| Encabezado | Título      |
| Párrafo    | Texto       |

Los anchos de las celdas pueden variar, como se muestra a continuación. La salida renderizada tendrá el mismo aspecto.

|Sintaxis|Descripción|
|-|-|
|Encabezado|Título|
|Párrafo|Texto|

Crear tablas con guiones y barras verticales puede resultar tedioso. Para acelerar el proceso, intente utilizar el [generador de tablas de Markdown](https://www.tablesgenerator.com/markdown_tables). Cree una tabla utilizando la interfaz gráfica y luego copie el texto generado con formato Markdown en su archivo.

#### Alineación

Puede alinear el texto de las columnas a la izquierda, a la derecha o al centro agregando dos puntos ( : ) a la izquierda, a la derecha o a ambos lados de los guiones dentro de la fila del encabezado.

| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |

#### Formateo de texto en tablas

Puede formatear el texto dentro de las tablas. Por ejemplo, puede agregar enlaces, código (palabras o frases en acentos graves ( ` ) únicamente, no bloques de código) y énfasis.

No puede usar encabezados, comillas en bloque, listas, reglas horizontales, imágenes o la mayoría de las etiquetas HTML.


### Bloques de código cercado

La sintaxis básica de Markdown le permite crear bloques de código sangrando las líneas con cuatro espacios o una tabulación. Si lo encuentra inconveniente, intente usar bloques de código delimitados. Dependiendo de su procesador o editor de Markdown, usará tres tildes ( ``` ) o tres tildes ( ~~~ ) en las líneas antes y después del bloque de código. ¿La mejor parte? No tienes que sangrar ninguna línea.

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

~~~
<!DOCTYPE HTML>
<html>
  <head>
    <meta charset="utf-8" />
    <title>Ejemplo1</title>
  </head>
  <body>
    <p>Párrafo de ejemplo</p>
  </body>
</html>
~~~

#### Resaltado de sintaxis

Muchos procesadores Markdown admiten el resaltado de sintaxis para bloques de código delimitado. Esta función le permite agregar resaltado de color para cualquier idioma en el que se haya escrito su código. Para agregar resaltado de sintaxis, especifique un idioma junto a las comillas graves antes del bloque de código delimitado.

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

``` html
<!DOCTYPE HTML>
<html>
  <head>
    <meta charset="utf-8" />
    <title>Ejemplo1</title>
  </head>
  <body>
    <p>Párrafo de ejemplo</p>
  </body>
</html>
```


### Notas de pie de página

Las notas al pie le permiten agregar notas y referencias sin saturar el cuerpo del documento. Cuando crea una nota al pie, aparece un número en superíndice con un enlace donde agregó la referencia de la nota al pie. Los lectores pueden hacer clic en el enlace para saltar al contenido de la nota al pie en la parte inferior de la página.

Para crear una referencia de nota al pie, coloque corchetes dentro un signo de intercalación seguido de un identificador. Los identificadores pueden ser números o palabras, pero no pueden contener espacios ni tabulaciones. Los identificadores solo correlacionan la referencia de la nota al pie con la nota al pie misma; en la salida, las notas al pie se numeran secuencialmente.

No es necesario poner notas a pie de página al final del documento. Puede colocarlos en cualquier lugar excepto dentro de otros elementos como listas, citas en bloque y tablas.

Una nota de pie de pagina simple,[^1] y una nota de pie de mas de una línea.[^notalarga]

[^1]: Primera nota de pie de pagina.

[^notalarga]: Un pie de pagina con multiple líneas.

    Aplicar sangría a los párrafos para incluirlos en la nota al pie.

    Añade tantos párrafos como quieras.


### ID de encabezado

Muchos procesadores Markdown admiten ID personalizados para encabezados ; algunos procesadores Markdown los agregan automáticamente. Agregar ID personalizados le permite vincular directamente a los encabezados y modificarlos con CSS. Para agregar un Id. de título personalizado, encierre el Id. personalizado entre llaves en la misma línea que el título.

`### Encabezado {#custom-id}`

En HTML:

`<h3 id="custom-id">Encabezado</h3>`


#### Vinculación a ID de encabezado

Puede vincular encabezados con ID personalizados en el archivo creando un vínculo estándar con un signo de número ( # ) seguido del ID de encabezado personalizado. Éstos se conocen comúnmente como enlaces ancla .

[ID de encabezado](#id-de-encabezado)

En HTML:

<a href="#id-de-encabezado">ID de encabezado</a>

Otros sitios web pueden vincularse al encabezado agregando el ID de encabezado personalizado a la URL completa de la página web (p. ej., [Heading IDs](https://www.markdownguide.org/extended-syntax#heading-ids)).


### Listas de definición

Algunos procesadores Markdown le permiten crear listas de definiciones de términos y sus definiciones correspondientes. Para crear una lista de definiciones, escriba el término en la primera línea. En la línea siguiente, escriba dos puntos seguidos de un espacio y la definición.

Primer Término
: Esta es la definición del primer término.

Segundo Término
: Esta es una definición del segundo término.
: Esta es otra definición del segundo término.

En HTML:

<dl>
  <dt>Primer Término</dt>
  <dd>Esta es la definición del primer término.</dd>
  <dt>Segundo Término</dt>
  <dd>Esta es una definición del segundo término.</dd>
  <dd>Esta es otra definición del segundo término.</dd>
</dl>


### Tachado

Para tachar palabras, use dos símbolos de tilde ( ~~ ) antes y después de las palabras.

~~El mundo es plano~~ .Ahora sabemos que el mundo es redondo.


### Listas de tareas

Las listas de tareas (también conocidas como listas de verificación y listas de tareas pendientes) le permiten crear una lista de elementos con casillas de verificación. En las aplicaciones de Markdown que admiten listas de tareas, se mostrarán casillas de verificación junto al contenido. Para crear una lista de tareas, agregue guiones ( - ) y corchetes con un espacio ( `[ ]` ) delante de los elementos de la lista de tareas. Para seleccionar una casilla de verificación, agregue un xentre paréntesis ( `[x]` ).

- [x] Escribir el comunicado de prensa
- [ ] Actualizar el sitio web
- [ ] Contactar con los medios


### Emojis

Hay dos formas de agregar emoji a los archivos de Markdown: copiar y pegar el emoji en el texto con formato de Markdown o escribir códigos abreviados de emoji.

:joy: :+1:


### Resaltar

Esto no es común, pero algunos procesadores Markdown le permiten resaltar texto. el resultado parece ==como esto==. Para resaltar palabras, use dos signos de igual ( == ) antes y después de las palabras.

Necesito resaltar estas ==palabras muy importantes==.

En HTML:  
Necesito resaltar estas <mark>palabras muy importantes</mark>.

### Subíndice

Para crear un subíndice, use un símbolo de tilde ( ~ ) antes y después de los caracteres.

H~2~O

En HTML:  
H<sub>2</sub>O


### Superíndice

Para crear un superíndice, use un símbolo de intercalación ( ^ ) antes y después de los caracteres.

X^2^

En HTML:  
X<sup>2</sup>


### Enlace de URL automático

Muchos procesadores de Markdown convierten automáticamente las URL en enlaces. Eso significa que si escribe http://www.example.com, su procesador Markdown lo convertirá automáticamente en un enlace aunque no haya usado corchetes.

### Deshabilitar vinculación de una URL

Si no desea que una URL se vincule automáticamente, puede eliminar el enlace denotando la URL como código con acentos graves.

`http://www.example.com`



