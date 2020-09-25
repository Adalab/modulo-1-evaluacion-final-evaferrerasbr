![Adalab](https://beta.adalab.es/resources/images/adalab-logo-155x61-bg-white.png)

# Evaluación final del módulo 1

El ejercicio de la evaluación plantea crear una página web desde cero en base a un diseño dado. La página construida tiene las siguientes secciones:

- Header: incluye un menú de navegación fijo y una sección hero que incluye la imagen de fondo, el h1 y el eslogan. Está maquetado con flex.
- Main: sección que abarca todo el cuerpo de la página. Está a su vez dividido en dos secciones: tips y reasons. Mientras que la primera está maquetada con elementos básicos como el padding o el ajuste del ancho de los elementos, la sección main-reasons utiliza grid. Cada elemento del grid es un partial, lo que permite replicar su estructura tantas veces como queramos editando los elementos necesarios (en este caso los títulos y descripciones).
- Footer: incluye dos menús de navegación correspondientes a los listados de secciones de la página y de redes sociales, así como un apartado de copyright. En los elementos de cada listado también se ha seguido el mismo sistema de partials. Todos estos elementos están maquetados con flex.
  El footer también incluye un botón que dirige al inicio de la página; este botón está posicionado de forma absoluta para situarlo en la división entre el footer y el main.

Como elementos adicionales a tener en cuenta, para la maquetación de esta página hemos utilizado un sistema de diseño que incluye variables, composición de clases y mixins para bloques de código repetitivos como las mediaqueries o los estilos de los botones.

Además, para mejorar la accesibilidad hemos incluido elementos como las etiquetas de tipo landmark o la subclase :focus en los botones.
