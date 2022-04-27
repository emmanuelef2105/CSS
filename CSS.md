# Curso de CSS

## Selección de elementos
En CSS podemos hacer selecciones por atributos, clases, id, etc.

```css
* { // Seleccionar todo
    background-color: red;
}

h1 { // Seleccionar el titulo o la etiqueta de un elemento
    color: blue;
}

.ejemplo { // Esto es una clase
    color: red;
    font-size: 20px;
}

#ejemplo { // Esto es un id
    color: red;
    font-size: 20px;
}

[ejemplo="loquesea"] { // Esto es un atributo
    color: red;
    font-size: 20px;
}

h2 p { // Seleccionar un elemento dentro de otro
    color: red;
    font-size: 20px;
}

.ejemplo:hover { // Seleccionar un elemento con una clase y hacer hover
    color: red;
    font-size: 20px;
}


```
## Jerarquía de elementos

![Jerarquía de los elementos en css](Imagenes\JerarquiaDeEstilos.PNG )

El estilo en línea es el siguiente:

```html
<p style="color: red">Ejemplo</p>

```
El important se puede hacer de la siguiente manera:

```css 
p {
    color: blue !important;
    font-size: 20px !important;
    font-weight: bold;
}
```
## Metodología BEM (Block Element Modifier)

```html
<div class="ejemplo">
    <input type="text" class="form__input">
</div>
```
    
```css

```