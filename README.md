![Adalab](https://beta.adalab.es/resources/images/adalab-logo-155x61-bg-white.png)

## Evaluación final del módulo 1

El ejercicio de la evaluación plantea crear una página web desde cero en base a un diseño dado con las siguientes secciones:

1. **Header**

Esta sección está **maquetada con flex** e incluye:

- Menú de navegación fijo.
- Sección hero que incluye imagen de fondo, h1 y eslogan.

2. **Main**

Sección que abarca todo el cuerpo de la página. Está a su vez dividido en dos secciones:

- Tips. Maquetada con **propiedades básicas de CSS** como padding, width o margins.
- Reasons. Utiliza **grid**. Cada elemento del grid es un **partial de HTML**, lo que nos permite replicar su estructura tantas veces como queramos editando los elementos necesarios (en este caso, títulos y descripciones).

3. **Footer**

Incluye dos menús de navegación correspondientes a los listados de secciones de la página y de redes sociales, así como un apartado de copyright. En los elementos del listado se ha seguido el mismo sistema de **reutilización de código mediante partials de HTML**. Todos los elementos están maquetados con **flex**.

El footer también incluye un botón que redirige al inicio de la página. Este botón está **posicionado de forma absoluta** para situarlo en la división entre el footer y el main.

### Bonus

Como elementos adicionales a tener en cuenta, para la maquetación de esta página hemos utilizado un sistema de diseño que incluye **variables, composición de clases y mixins** para bloques de código repetitivos como las mediaqueries o los estilos de los botones.

Además, para mejorar la accesibilidad hemos incluido elementos como las **etiquetas de tipo landmark** o la **subclase :focus** en los botones.
