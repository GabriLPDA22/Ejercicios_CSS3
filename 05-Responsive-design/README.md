# Diseño Responsivo en CSS

El diseño responsivo asegura que tu página se vea bien en cualquier dispositivo, ajustándose al tamaño de la pantalla.

## Ejemplo de Media Query
Cambia el diseño basándote en el ancho de la pantalla del dispositivo.

```css
.contenedor {
  width: 100%;
}

@media (min-width: 768px) {
  .contenedor {
    width: 50%;
  }
}

```

## Consejos Adicionales

- Diseña primero para móviles (Mobile First), comenzando por la pantalla más pequeña y expandiendo el diseño a medida que la pantalla se agranda.
- Utiliza un enfoque de diseño progresivo, asegurándote de que la funcionalidad básica esté disponible para todos los usuarios, independientemente del dispositivo.
- Prueba tu diseño en tantos dispositivos reales como sea posible, así como en emuladores y herramientas de desarrollo del navegador.

## Recursos Adicionales

- [Responsive Web Design Basics on Google Developers](https://developers.google.com/web/fundamentals/design-and-ux/responsive)
- [Responsive Design Testing Tool](https://responsivedesignchecker.com/)
- [Media Queries for Standard Devices](https://css-tricks.com/snippets/css/media-queries-for-standard-devices/)
