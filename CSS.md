# CSS Cascading Style Sheets

Describe cómo los elementos de HTML se mostrarán en la pantalla, papel u otro medio.

Se puede agregar a un elemento de HTML en 3 formas:

* En línea (inline): utilizando el atributo `style`.

`<h1 style="color:blue;">This is a Blue Heading</h1>`

* Interna: Utilizando `<style>` en la sección `<head>`.

`<head>
<style>
body {background-color: powderblue;}
h1   {color: blue;}
p    {color: red;}
#p01 {
    color: blue;
}
</style>
</head>`

* Externa: Utilizando un archivo CSS externo.

`<head>
  <link rel="stylesheet" href="styles.css">
</head>`

## Propiedades

* `color`
* `font-family`
* `font-size`
* `border`
* `padding`
* `margin`

