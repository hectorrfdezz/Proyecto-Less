# Proyecto LESS – Mini web corporativa

## Descripción

Este proyecto es una adaptación del proyecto original en **SASS** a **LESS**
para la asignatura de *Diseño de Interfaces Web* del IES Mar de Cádiz.
La web consta de tres páginas principales: **Inicio**, **Información** y
**Contacto**. Todos los estilos se gestionan mediante LESS para mejorar la
organización y mantenibilidad del código, utilizando variables, mixins y
anidamiento de reglas. Además, se implementa un *footer* que siempre se
mantiene al pie de la página y el contenido ocupa el alto completo de la
pantalla.

## Tecnologías

- **HTML5** para la estructura de las páginas.
- **LESS** como preprocesador CSS.
- **CSS** generado automáticamente a partir de `less/main.less`.
- Se recomienda usar **Visual Studio Code** con una extensión de compilación
  de Less o `lessc` en la línea de comandos para generar el CSS.

## Estructura del proyecto

El archivo `main.less` importa todos los parciales mencionados arriba.
Al compilarlo se generará `css/main.css`, que es el fichero que se enlaza
desde los HTML. Durante el desarrollo puedes utilizar el compilador de
Less en el navegador (ver las etiquetas `<link rel="stylesheet/less" ...>`
en las páginas) o generar el CSS de forma offline.

## Cómo usarlo

1. Abre la carpeta del proyecto en tu editor de código.
2. Instala un compilador de Less (por ejemplo, `lessc` desde npm) o utiliza
   una extensión de Less para VS Code.
3. Compila `less/main.less` y guarda el resultado en `css/main.css`.
4. Abre cualquiera de las páginas HTML en tu navegador. Si prefieres
   trabajar sin compilar, puedes dejar el compilador de Less incluido en
   los HTML (`less.min.js`) para que el navegador genere los estilos en
   caliente.

## Contenido principal

-**Variables globales** para colores, tipografía y espaciado (`less/abstracts/variables.less`).
-**Mixins reutilizables** para centrar contenido, layouts de grid, botones,
  contenedores de vídeo, etc. (`less/abstracts/mixins.less`).
-**Anidamiento** para mantener un CSS limpio y jerárquico.
-**Footer fijo** en la parte inferior de la página.
-**Diseño adaptable** gracias al uso de unidades relativas y flexbox/grid.


## Integrante del grupo:

Tomás García Chaves

Hugo Gil Bailón

Adulis Esteban López Tirado

Hector Ramos Fernández