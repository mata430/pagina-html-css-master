# Creando pagina web con HTML Y CSS

[Video](https://www.youtube.com/watch?v=8-RC-Q7Wtzc&ab_channel=deivchoi)

> :bulb: **Tip:** No Frameworks Full

La imagen la colocamos dentro de un div por que asi es mas nanejable.

## Estilos Generales

vamos a empezar el css con mobile-first, esto para escribir menos codigo.

<details>
<summary> Como hacer que el boton se direccione a una pagina?</summary>
Hay que envolver el botton en un form.

```html
<form action="https://www.google.com/">
  <button>APLICA YA!</button>
</form>
```

</details>

codigo <span style="color:red"> **DRY**</span>: Don't Repeat Yourself (No repitas tu codigo)

## Estilizado CSS

1. **container**: Centramos el contenido de los textos y subtitulos

```css
.container {
  max-width: 1400px;
  margin: auto;
}
```

2.  **header**

Centramos el header y estilizamos el logo

```css
header .container {
  display: flex;
  flex-direction: column;
  align-items: center;
}
```

me quede en seccion caracteristicas
