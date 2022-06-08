# HTML Semantico
Es usar las etiquetas especificas para cada situacion correspondiente , si queremos mostrar algo abajo de la pagina se usa `<flooter>`, usar las etiquetas correctas nos ayudara a
<br>
- Tener un codigo accesible
- Mejora tu posicionamiento SEO 
- Codigo mas claro
<br>

## Etiquetas de HTML mas usadas
**Layout**: diseño de la pagina , estructura principal
`<header> <nav> <section> <article> <aside> <footer>`
<br>

**Enlazes**: `<a>`
<br>

**Textos**: `<h1> ... <h6> <p> <span>`
<br>

**Formularios**: `<form> <input> <label> <button>`
<br>

**Imagenes y Video**: `<img> <svg> <iframe> <video>`
<br>

**Listas**: `<ul> <li> <ol>`


[+Etiquetas HTML](https://htmlreference.io/)

<br>

# Tipos de selectores mas usados
- DE tipo     -->    `div{}`
- De clase    -->    `.elemento{}`
- De ID       -->    `#id-del-elemento`
- De Atributo -->    `a[href=""]{}`
- Universal   -->    `*{}`
<br>

[Colores HTML](https://htmlreference.io/)


### Selectores Combinadores
- Descendientes --> `div p`
- Hijo Directo --> `div > p`
- Elemento Adyacente --> `div + p`
- General de hermansos --> `div ~ p`

---
## PseudoClases
Nos permite captar las acciones del usuario para realizar un determinado accion, por ejemplo el hover si pasamos el mouse por ese campo realiza tal accion.
- :active
- :focus
- :hover
- :nth-child(n)

[+PseudoClases](https://css-tricks.com/pseudo-class-selectors/)
## PseudoElementos
Nor permite llegar a ciertos elementos de HTML que no son accesibles con selectores.
- ::after
- ::before
- ::first-letter
- ::placeholder

[+PseudoElementos](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements)


# CSS (Cascading Style Sheet)
Cascaca significa que el orden de las reglas en CSS importa.
```CSS
h1 {
    color: red;
}
h1 {
    color: blue;
}
/*Cual se mostrara primero??*/
```
## Especifidad
Es la prioridad que tiene un elemento de css por encima del otro
- !important (10000 puntos) `color: red !important;`
- estilo en linea (1000 puntos) ej: `<h1 style="color:red;">texto</h1>`
- #id (100 puntos)
- clases, atributos y pseudoClases (10 puntos)
- elementos y pseudoElementos (1 punto)
- selector universal (0 punto)

Si mostramos que elemento tiene mayor relevancia , se mostraria con puntos 

[Calcular la especifidad](https://specificity.keegan.st/)

# Tipos de Display
Es el tipo de visualizacion que tienen los elementos. Los elementos en linea no tienen propiedades de tipo Block
- Block
- Inline
- Inline-block
- FlexBox
- Grid

[FlexBox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

[Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)


# Modelo de caja
Todas las cajas tienen un **Margin** , **Border** , **Padding** y un **Content**. 

![image](https://blog.hubspot.com/hs-fs/hubfs/Google%20Drive%20Integration/Update%20css%20margin%20vs%20padding-2.png?width=650&name=Update%20css%20margin%20vs%20padding-2.png)
