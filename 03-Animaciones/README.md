# Animaciones en CSS

Las animaciones pueden hacer que una interfaz de usuario sea más interesante y mejoran la experiencia de usuario al proporcionar retroalimentación visual, guiar tareas y llamar la atención sobre ciertas áreas.

## Propiedades Clave
- **Transitions:** Permite cambiar los valores de las propiedades CSS a lo largo del tiempo.
- **Animations:** Brinda control total sobre los pasos de la animación, su duración, repetición y más.


## Ejemplo de Animación Simple
Una animación que cambia el color de fondo de un elemento cuando el usuario pasa el cursor sobre él.

```css
.elemento-animado:hover {
  animation: cambio-color 2s infinite;
}

@keyframes cambio-color {
  0% { background-color: #ffffff; }
  100% { background-color: #0000ff; }
}

```
Al pasar el cursor sobre .elemento-animado, el fondo cambiará entre blanco y azul.

![Animación de cambio de color](./GIF/PrevisualizacindeAnimacionCSS.gif)


## Ejemplo de Transición
```css
.button {
  transition: background-color 0.3s ease;
}
.button:hover {
  background-color: #3498db;
}
```
Al pasar el cursor sobre .button, su color de fondo cambiará suavemente a azul.

![Boton](./GIF/BotnconEstilodeTransicion.gif)


## Ejemplo de Animación Keyframes

```css
.loading {
  animation: spin 2s linear infinite;
}
@keyframes spin {
  from { transform: rotate(0deg); }
  to { transform: rotate(360deg); }
}
```

Un elemento con la clase .loading rotará continuamente para indicar un proceso de carga.

![Carga](./GIF/AnimacindeCarga.gif)

## Consejos Adicionales

- Mantén las animaciones simples y sutiles para no distraer demasiado al usuario.
- Usa `will-change` para optimizar las animaciones, pero con precaución y solo cuando sea necesario.
- Considera las implicaciones de accesibilidad de las animaciones y proporciona controles para que los usuarios las detengan si lo necesitan.

## Recursos Adicionales

- [CSS Animations on MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Animations/Using_CSS_animations)
- [CSS Tricks on Animation](https://css-tricks.com/almanac/properties/a/animation/)
- [Animation Performance 101](https://www.smashingmagazine.com/2016/12/gpu-animation-doing-it-right/)
