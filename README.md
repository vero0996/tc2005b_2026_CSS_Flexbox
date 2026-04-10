# tc2005b_2026_CSS_Flexbox

Este repositorio contiene una barra de navegación diseñada con CSS.

## GitHub Pages
Puedes ver el resultado en vivo aquí:
[Enlace al sitio](https://vero0996.github.io/tc2005b_2026_CSS_Flexbox/)

## Propiedades CSS Utilizadas

Para este diseño, utilicé varias propiedades clave de CSS que permiten el control total del estilo:

### 1. `display: flex;`
Es el corazón de la estructura del menú. Se aplicó al contenedor `<ul>` para alinear los elementos de la lista en una fila horizontal de forma automática y permitir un control sencillo sobre el espaciado y la alineación.

### 2. `text-decoration: underline;`
Esta propiedad se utilizó en los enlaces (`<a>`) para añadir un subrayado clásico. Es fundamental para la accesibilidad, ya que ayuda al usuario a identificar rápidamente que el texto es un elemento clicable.

### 3. `transition: all 0.4s ease;`
Sirve para crear animaciones suaves. En lugar de que el color o la posición cambien de golpe al pasar el mouse (`:hover`), esta propiedad hace que el cambio sea fluido y elegante durante 0.4 segundos, mejorando la experiencia del usuario.