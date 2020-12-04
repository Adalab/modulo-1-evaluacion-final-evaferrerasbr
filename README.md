## Evaluación final del módulo 1

![Homepage]()

## Descripción

El ejercicio de evaluación final consiste en maquetar una web responsive en base a un diseño dado utilizando **html** y **SASS**.

Además, para esta maquetación hemos utilizado **npm** y **gulp**.

## Estructura

```
src
├── components
│ ├── App.js - Controla el estado de la aplicación y el renderizado de los componentes
│ ├── CharacterList.js - Listado con los personajes que se mostrarán en pantalla
│ ├── CharacterCard.js - Artículo con cada tarjeta de personaje del listado
│ ├── CharacterDetail.js - Tarjeta con detalles del personaje a la que accedemos mediante React router
│ ├── Filters - Formulario con los filtros por nombre, género, status y para ordenar alfabéticamente
│ ├── Extras - Contiene componentes que añaden mejoras a la experiencia de usuaria
│ ├── Header.js
│ └── Footer.s
├── images
├── images-readme
├── services
│ └── api.js - Gestiona la llamada a la API y captura el error si se produce
│ └── localstorage.js - Almacena la búsqueda de la usuaria en el local storage
├── stylesheets - Las hojas de estilo siguen la misma estructura que los componentes
└── index.js
```

El proyecto tiene las ramas principales máster y dev. Además, hemos utilizado el **sistema de Issues de Github** para organizar el trabajo. Cada una de las ramas del proyecto se corresponde con un issue, que tiene detalladas las tareas realizadas. Se han marcado como "bonus" todas las tareas extra que no eran requerimientos necesarios para la evaluación.

## Descarga e instalación

Para usar este proyecto en tu equipo local:

1. Descarga el repositorio
2. Instala node
3. Haz **npm install** para instalar las dependencias
4. Haz **npm start**

## Demo

Para ver la aplicación en funcionamiento puedes visitar el [siguiente enlace](https://evaferrerasbr.github.io/modulo-3-evaluacion-final-evaferrerasbr/#/), que también se encuentra disponible en la descripción del proyecto.

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
