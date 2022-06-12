# HTML Semantico
Es usar las etiquetas especificas para cada situacion correspondiente , si queremos mostrar algo abajo de la pagina se usa `<flooter>`, usar las etiquetas correctas nos ayudara a
<br>
- Tener un codigo accesible
- Mejorar tu posicionamiento SEO 
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
- General de hermanos --> `div ~ p`

---
## PseudoClases
Nos permite captar las acciones del usuario para realizar un determinado accion, por ejemplo el hover si pasamos el mouse por ese campo realiza tal accion.
- :active
- :focus
- :hover
- :nth-child(n)

[+PseudoClases](https://css-tricks.com/pseudo-class-selectors/)
## PseudoElementos
Nos permite llegar a ciertos elementos de HTML que no son accesibles con selectores.
- ::after
- ::before
- ::first-letter
- ::placeholder

[+PseudoElementos](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements)


# CSS (Cascading Style Sheet)
Cascada significa que el orden de las reglas en CSS importa.
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
- estilo en linea (1000 puntos) `<h1 style="color:red;">texto</h1>`
- #id (100 puntos)  `#id{}`
- clases, atributos y pseudoClases (10 puntos)
- elementos y pseudoElementos (1 punto)
- selector universal (0 punto)

Si mostramos que elemento tiene mayor relevancia , se mostraria con puntos 

[Calcular la especifidad](https://specificity.keegan.st/)

# Tipos de Display
Es el tipo de visualizacion que tienen los elementos. Los elementos en linea no tienen propiedades de tipo Block.
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

# Colapso de margenes
Sucede cuando hay dos elementos bloque de forma vertical y se basa en no respetar el margen que establecemos nosotros , por ejemplo si en cada bloque colocamos `margin:20px` la distancia entre bloque es de 40px pero el resultado es 20px. No sucede cuando el contenedor es de Flexbox , Grid o elementos que no sean de bloque y el resultado mostrara una distancia de 40px.

# Posicionamiento
Nos ayuda a ubicar los elementos en una posicion determinada
Tenemos diferentes tipos de posicionamiento: 
- Relative
- Absolute
- Fixed
- Sticky
- Static
- initial

![image](https://www.csssolid.com/images/csspositions/css-position-all.png)

## Z-INDEX y el contexto de apilamiento
Al cambiar el orden de las etiquetas , uno aparece por encima de otro , por ende importa la jerarquia interna para determinar que se muestra primero. Z-Index funciona con determinados `position:` . 

---
#### Para mas informacion de propiedades en CSS
[Propiedades CSS](https://cssreference.io/)

# Unidades de medidas
### Absolutos
Medidas que no dependen de nadie mas para ser ellas mismas <br>
`px pt pc in cm mm`
### Relativos
Las medidas relativas dependen de algo para poder calcular su medida, por ejemplo, los porcentajes dependen del elemento padre, los em rem dependen del font-size, los vw y vh dependen del tamaño del viewport. <br>
`rem em vw vh vmin vmax ex ch`

# Responsive Design
Cambiar los estilos de nuestra pagina en determinados tamaños , ya sea mostrar por celular , mostrar por una pantalla pequeña, etc.
```css
    /*Desde 200 para arriba*/
    @media (min-width: 200px) {

    }
    /*Hasta 200 para abajo*/
    @media (max-width: 200px) {
        
    }
```
# Arquitecturas CSS
Los objetivos a tener en cuenta a la hora de realizar una buena arquitectura es que sea predecible, reutilizable, mantenible y escalable. Las Buenas practicas para que se cumpla los objetivos serian los lineamientos, documentacion, estandares y componentes. <br>
[Arquitectura BEM](https://platzi.com/blog/bem/)

## Realizar Retos
https://www.frontendmentor.io/

https://platzi.com/comunidad/platziwebchallange-semana-1-2/

https://coderbyte.com/challenges

https://www.codewell.cc/challenges

https://codepen.io/

https://cssbattle.dev/
