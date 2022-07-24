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
    - [Enlases (Links)](#enlases-links)
    - [Imagen](#imagen)
    - [Bloque de código](#bloque-de-código)
    - [Carácter de Escape](#carácter-de-escape)
    - [HTML](#html)
  - [Sintaxis Extendida](#sintaxis-extendida)
    - [Tablas](#tablas)
    - [Bloques de código cercado](#bloques-de-código-cercado)
    - [Notas de pie de página](#notas-de-pie-de-página)
    - [ID de encabezado](#id-de-encabezado)
    - [Listas de definición](#listas-de-definición)
    - [Tachado](#tachado)
    - [Listas de tareas](#listas-de-tareas)
    - [Emojis](#emojis)
    - [Resaltar](#resaltar)
    - [Subíndice](#subíndice)
    - [Sobreíndice](#sobreíndice)
    - [Enlace de URL automático](#enlace-de-url-automático)
    - [Deshabilitar vinculación de una URL](#deshabilitar-vinculación-de-una-url)


<br/>
<br/>

## Sintaxis Basica

### Encabezados
Mejores prácticas de encabezado  
Las aplicaciones de Markdown no se ponen de acuerdo sobre cómo manejar un espacio que falta entre los signos de número (#) y el nombre del encabezado. Por compatibilidad, siempre ponga un espacio entre los signos numéricos y el nombre del encabezado.

```
# Encabezado 1
## Encabezado 2
### Encabezado 3
#### Encabezado 4
##### Encabezado 5
###### Encabezado 6
```

Otra alternativa para colocar encabezados, aunque de dos niveles, serian dos == para el primer nivel y dos -- para el segundo nivel.


| Markdown                                              | Resulatado               |
| ----------------------------------------------------- | ------------------------ |
| Nivel de encabezado 1<br/>  ===============           | <h1>Heading level 1</h1> |
| Nivel de encabezado 2<br/>  ------------------------- | <h2>Heading level 1</h2> |



### Párrafos
Para crear párrafos, use una línea en blanco para separar una o más líneas de texto.

Ejemplo:

Lorem ipsum dolor sit amet, fames ac ante ipsum primis in faucibus. Aenean pulvinar vehicula felis, a suscipit ante interdum quis. Morbi luctus nibh ligula, eget dapibus lacus facilisis sit amet. Proin mollis pretium est vel aliquam. Aenean iaculis consectetur finibus. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Proin in aliquam est. Aenean blandit felis maximus interdum convallis. Donec nec vulputate purus. Sed eleifend dui id pretium consectetur. Fusce imperdiet quam non dapibus lobortis. Praesent dapibus nibh in elit eleifend commodo.

Cras id faucibus nisi, sed gravida leo. Donec et interdum ex, ut vestibulum ipsum. Donec vehicula efficitur pellentesque. Aliquam facilisis lectus nisl. Mauris euismod blandit mi, ultrices feugiat odio varius et. Fusce imperdiet in quam ut bibendum. Nunc nisi lorem, euismod vitae nulla ac, vestibulum pharetra eros.

### Saltos de línea

Para hacer un salto de línea coloque dos espacios al final de la linea o `<br/>`.

Primera línea  
Segunda línea<br/>
Tercera línea  

### Estilos de fuentes

Poniendo el texto en negrita, cursiva, Tachar y Subrayar.

*Cursiva*  
**Negrita**  
~~Tachar~~  
_Subrayar_

**Lorem ipsum** dolor sit amet, fames ac ante *ipsum* primis in faucibus. Aenean pulvinar vehicula felis, a suscipit ante interdum quis. _Morbi_ luctus nibh ligula, eget dapibus lacus facilisis sit amet. Proin mollis pretium est vel aliquam. Aenean iaculis ***consectetur finibus***. Orci varius <strong>natoque penatibus</strong> et magnis dis <em>parturient montes</em>, nascetur ridiculus mus. Proin in aliquam est. Aenean blandit felis maximus interdum convallis. Donec nec vulputate purus. Sed eleifend dui id pretium consectetur. Fusce imperdiet quam non dapibus lobortis. Praesent dapibus nibh in elit eleifend commodo.

### Bloque de citado

Para crear una cita en bloque, agregue un >delante de un párrafo.

>Es en las noches de diciembre, cuando el termómetro está a cero, cuando más pensamos en el sol <P align="right">Los miserables, Victor Hugo<p/>

Bloque de cita anidado:

>**Lorem ipsum** dolor sit amet, fames ac ante *ipsum* primis in faucibus. 
>
>>Aenean pulvinar vehicula felis, a suscipit ante interdum quis. 


### Lista desordenada

Para crear una lista desordenada, agregue guiones (-), asteriscos (*) o signos más (+) delante de las líneas de pedido. Colocar sangria ha uno o más elementos para crear una lista anidada.

- Primer valor
- Segundo valor
- Tercer valor
    - Valor Indented item
      - Elemento
    - Indented item
- Fourth item


Si necesita comenzar un elemento de lista desordenado con un número seguido de un punto, puede usar una barra invertida (\\) para escapar del punto.

- 1968\. A great year!
- I think 1969 was second best.


### Lista ordenada

Para crear una lista ordenada, agregue elementos de línea con números seguidos de puntos. Los números no tienen que estar en orden numérico, pero la lista debe comenzar con el número uno.

1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item

<br/>

Código en HTML:

<ol>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item
    <ol>
      <li>Indented item</li>
      <li>Indented item</li>
    </ol>
  </li>
  <li>Fourth item</li>
</ol>


### Línea horizontal

Para crear una línea horizontal, use tres o más asteriscos (***), guiones (---) o guiones bajos (___) en una sola línea.

---


### Enlases (Links)

Para crear un enlace, encierre el texto del enlace entre corchetes ([Texto a mostrar]) y luego sígalo inmediatamente con la URL entre paréntesis (https://googe.com.do).

Realice busquedas en [Google](https://googe.com.do).

Colocar un título, escríbalo entre comillas después de la URL.

Volver al [`Índice`](#índice).

Realice busquedas en [_**Google**_](https://googe.com.do "Click aquí").

### Imagen

Para agregar una imagen, agregue un signo de exclamación ( !), seguido del texto alternativo entre paréntesis y la ruta o URL del recurso de imagen entre paréntesis. Opcionalmente, puede agregar un título entre comillas después de la ruta o URL.

![Markdown](.\markdown-mark-white.svg "Markdown")


![Vivaldi logo](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/1920px-Markdown-mark.svg.png)


### Bloque de código

Se utiliza el acento grave para identificar código, y corchetes para identificar el lenguaje de programación.

`Código`  
``Use `code` in your Markdown file.``


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

### HTML

## Sintaxis Extendida

### Tablas
### Bloques de código cercado
### Notas de pie de página
### ID de encabezado
### Listas de definición
### Tachado
### Listas de tareas
### Emojis
### Resaltar
### Subíndice
### Sobreíndice
### Enlace de URL automático
### Deshabilitar vinculación de una URL
