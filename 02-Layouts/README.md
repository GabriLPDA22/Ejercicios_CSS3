# Layouts en CSS

Los layouts en CSS son fundamentales para estructurar el contenido de las páginas web de manera lógica y atractiva.

## Ejemplo de Uso de Flexbox
Flexbox es una herramienta poderosa para crear diseños flexibles y responsivos.

```html
<div class="contenedor-flex">
  <div class="elemento-flex">Item 1</div>
  <div class="elemento-flex">Item 2</div>
  <div class="elemento-flex">Item 3</div>
</div>
```
```css
.contenedor-flex {
  display: flex;
  justify-content: space-around;
}
.elemento-flex {
  flex: 1;
}

```

Este ejemplo muestra un contenedor flex con tres elementos que se distribuyen con espacio alrededor.


## Ejemplo de Uso de Grid

CSS Grid permite crear complejas estructuras de diseño de página con filas y columnas.

```html 
<div class="contenedor-grid">
  <div class="elemento-grid">Header</div>
  <div class="elemento-grid">Main content</div>
  <div class="elemento-grid">Sidebar</div>
  <div class="elemento-grid">Footer</div>
</div>
```
```css
.contenedor-grid {
  display: grid;
  grid-template-columns: 1fr 3fr;
  grid-template-rows: auto;
  gap: 10px;
}
.elemento-grid {
  border: 1px solid #333;
}
``` 
Este fragmento crea un layout básico de página con un header, contenido principal, sidebar y footer.

## Consejos Adicionales

- Utiliza unidades relativas como `%`, `vw`, `vh`, `em`, o `rem` para tamaños y espacios para mejorar la flexibilidad y la respuesta del diseño.
- Experimenta con diferentes valores de `align-items` y `justify-content` en Flexbox para ver cómo afectan el alineamiento y distribución de los elementos.
- Para CSS Grid, practica con `grid-template-areas` para un manejo más visual de las áreas de tu grid.

## Recursos Adicionales

- [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [Learn CSS Layout](https://learnlayout.com/)
