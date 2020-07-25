## Pseudoclases
Una pseudoclase se usa para definir un estado especial de un elemento. <br>
Por ejemplo: <br>

+ Diseño de un elemento cuando el usuario pase el mouse sobre él.
+ Estilo de enlaces visitados.
+ Darle estilo a un elemento cuando se enfoca.

Sintaxis de las pseudoclases: <br>

    selector: pseudoclases {
        property: value;
    }    

**Link no visitado**

    a:link{
        color: #red;
    }
**Link visitado**

    a:visited{
        color: pink;
    }
**Mouse sobre el link**

    a:hover {
        color: green;
    }
**Link seleccionado**
    
    a:active {
        color: blue;
    }
**NOTA:** <br>
`a:hover` debe venir después de `a:link` y `a:visited`. <br>
`a:active` debe venir después de `a:hover`. <br>

+ Las pseudoclases pueden combinarse con clases CSS. <br>

Ejemplo de usos diferentes a `<a>`: <br>

`<div>`
    
    div:hover {
        background-color: blue
    }

## DESPLAZAMIENTO SOBRE UN ELEMENTO PARA MOSTRAR UNA ETIQUETA OCULTA
Desplazamiento sobre un elemento `<div>` para mostrar un elemento `<p>`