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

---
## Tipos de selectores mas usados
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
Nor permite llegar a ciertos elementos de HTML que no son accesibles con selectores
- ::after
- ::before
- ::first-letter
- ::placeholder

[+PseudoElementos](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements)

---