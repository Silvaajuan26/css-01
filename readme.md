# CSS

- Es un lenguaje para dar estilos a la web (1996)

## SINTAXIS

-   Como se puede establecer codigo CSS

```css
h1 {
    color: red;
}
```
- h1 : Selector
- color: Propiedad
- red : Valor

## CONCEPTOS IMPORTANTES  CSS

- 4 Concetos importantes de CSS

### SELECTORES

- Indica a que elemnto o elementos, se aplicara estilos.

```css
/* Selector de Etiqueta*/
h1 {
    color: red;
}

/* Selector de Descendencia*/
nav ul li a {
    color: red;
}
```
### HERENCIA

- Elementos ancentros heredan propiedades a sus descendientes.

```html
    <p>Hola mundo <a href="">Este es un enlace</a></p>
    ```
```css
p {
    color :peru;
}
a {
color: inherit;
}
```

### CASCADA

- Significa que los estilos que llegan en ultimo lugar, sobreescriben a los de antes.
- La especificidad vence a la cascada

```css
h1{
    color: red;
}

h1{
    color: blue;
}
```

### ESPECIFICIDAD

- Es un valor numerico qe adquieren los selectores y se aplica cuando hay confictos.

```html
<!---Selector de Etiqueta (1) -->

<!---Selector de clase (10) -->

<!---Selector de ID (100) -->

<!---INLINE (1000) -->

<!---IMPORTANT (INFINITE) -->
```

## ESTILOS DE TEXTOS

