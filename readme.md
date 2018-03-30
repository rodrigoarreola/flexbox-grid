# Index

## Practice 1

[link to practice](https://codepen.io/rodrigoarreola/pen/bvLWBZ) 

### Content
1. Flex container
2. Flex item
3. Flex lines
4. Main axis and cross axis
    4.1. Main size, main start, main end
    4.2. Cross size, cross start, cross end


`flex-wrap: wrap;` make the items ocupe their original size

`flex-direction: row-reverse;`  each line it's independient 
 I mean, in the example this proves that, beacuse each line aplies the `row-reverse`

 ## Practice 2

 [link to practice](www.google.com)

 ### Cheat sheet

#### Propiedades de los elementos padres

1. `display: flex | inline-flex;`  
    Define una caja flexible de bloque o de línea

2. `flex-direction: row | row-reverse | column | column-reverse;`  
    Define el eje principal y el transversal de la caja flexible
    row x - principal | y - transversal
    column x - transversal | y - principal

3. `flex-wrap: nowrap | wrap | wrap-reverse;`  
    Determina la existencia o no de saltos de línea y su sentido
    
4. `justify-content: flex-start | flex-end | center | space-between | space-around;`  
    Alineación de los hijos en el eje principal (espacio sobrante)

5. `align-items: stretch | flex-start | flex-end | center | baseline;`  
    Alineacion de los hijos en el eje transversal (espacio sobrante) cuando NO HAY saltos de línea `(flex-wrap: no-wrap;)`

6. `align-content: stretch | flex-start | flex-end | center | space-between | space-around;`  
    Alineación de los hijos en el eje transversal (espacio sobrante) cuando SI HAY saltos de línea `(flex-wrap: wrap | wrap-reverse;)`

## Practice 3

Example of how to use `flex-direction` and `order` in order to build a simple template  
with a `main` tag and an `aside` tag

[link to practice](https://jsfiddle.net/rodrigoarreola/ypuqd5wr/)

### Cheat sheet

#### Propiedades de los elementos hijos

1. `order: $num;`  
    Esta propiedad puede cambiar el orden de los elementos  
    Por default todos los items tienen valor 0, es decir si a un item le ponemos  
    valor 1 este se iría al final, ejemplo:  
    item 1 (0), item 3 (0), item 2 (1)

2. `flex-grow: $num;`  
    Especifica cuanto puede crecer un item en relación al resto de los otros items

3. `flex-shrink: $num;`  
    Especifica cuanto puede encogerse un item en relación al resto de los otros items

4. `flex-basis: $num px;`  
    Establece el tamaño inicial de los elementos

5.  `flex: flex-grow flex-shrink flex-basis;`  
    Es un shorthand para los elementos anteriores

6.  `align-self: center | auto | baseline | flex-start | flex-end | inherit | stretch;`  
    Especifica la alineación del elemento seleccionado dentro  
    de su contenedor esta propiedad sobreescribe la alineación  
    por defecto establecida en `align-items` por el contenedor

## Practice 4

In this practice I've build a holy grail layout with flexbox

[link to practice](https://jsfiddle.net/rodrigoarreola/L7mp1j1h/)
    
## Practice 5

In this practice I've build a simple animated slider only with flexbox

[link to practice](https://jsfiddle.net/rodrigoarreola/wvmph1LL/)

## Practice 6

In this practice I've build a simple splited layout
[link to practice](https://jsfiddle.net/rodrigoarreola/4Lp8nLbg/)

Another links of interest:
* [Best image placeholders](https://www.johanbostrom.se/blog/the-best-image-placeholder-services-on-the-web)
* [Lorempixel](http://lorempixel.com/) this is great because you can select a topic for the image  
  the usage is verys simple `http://lorempixel.com/{width}/{height}/{topic}/`
* [Placeholder](https://placeholder.com/) the usage is like this `http://via.placeholder.com/{width}x{height}`

## Practice 7

In this practice I've build a product grid, the classes of this practice are set according the [BEM](https://css-tricks.com/bem-101/) methodology  

[Why BEM?](https://blog.decaf.de/2015/06/24/why-bem-in-a-nutshell/)

[BEM with Sass](https://assist-software.net/blog/css-guideline-tutorial-bem-sass)

[BEM's official site](http://getbem.com/)  

[link to practice](https://jsfiddle.net/rodrigoarreola/f1jpf0uy/)

## Practice 8

This little practice it's about total center in elements with flexbox

[link to practice](https://jsfiddle.net/rodrigoarreola/jbhgg5ox/)

## Practice 9

Build of a blog layout, the classes were set according the BEM methodology

[link to practice](https://jsfiddle.net/rodrigoarreola/yve0qpuq/)

## Practice 10

Simple example of fixed header and footer using flexbox

[link to practice](https://jsfiddle.net/rodrigoarreola/ypyok7xu/)


