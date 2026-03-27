# Proyecto Gaming 

Este repositorio contiene el desarrollo de una página informativa sobre la industria de los videojuegos. El proyecto ha pasado por un proceso de refactorización y optimización para mejorar tanto su estructura técnica como su apariencia visual.

##  Mejoras Realizadas

Se realizaron dos tipos de intervenciones en el código original:

### 1. Acciones Correctivas (Limpieza y Estructura)
* Separación de Intereses:** Se eliminaron los estilos en línea (`style="color:..."`) y los atributos de tamaño directamente en el HTML (`width`, `height`), trasladando toda la lógica visual al archivo CSS externo para un código más limpio.
* Corrección de Sintaxis Semántica:** * Se corrigió el anidamiento de etiquetas: los elementos `<h3>` e `<img>` ahora están correctamente contenidos dentro de etiquetas `<li>`.
    * Se reorganizó la estructura del documento, asegurando que todas las etiquetas visuales estén dentro del `<body>` y que el `<nav>` sea independiente del `<header>` para permitir efectos avanzados de posicionamiento.
* **Modernización de Layout:** Se eliminó el uso de `float: left` en la navegación (técnica obsoleta) y se reemplazó por un modelo de caja más actual y flexible.

### 2. Acciones Evolutivas (Nuevas Funcionalidades)
* Navegación Sticky (Barra Fija):** Se implementó `position: sticky` en el menú. A diferencia de la versión original, ahora el menú acompaña al usuario durante el scroll, mejorando la navegación.
* UX de Desplazamiento:** Se añadió `scroll-behavior: smooth` y `scroll-margin-top`. Esto permite que, al hacer clic en los enlaces, el salto sea suave y la barra fija no tape los títulos de las secciones.
* Optimización de Listas:** Se aplicó `list-style-type: none` y centrado de texto para que las listas se integren armoniosamente con el diseño centrado de la página, eliminando los puntos negros desalineados por defecto.
* Micro-interacciones:** Se agregaron efectos de `transition` y `transform: scale` en las imágenes y enlaces para dar una sensación de interactividad moderna y profesional.

## Estructura del Proyecto
* `index.html`: Estructura semántica del sitio.
* `assets/css/style.css`: Estilos, animaciones y diseño responsivo.
* `assets/img/`: Recursos visuales del proyecto.
