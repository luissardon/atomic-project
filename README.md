# The Atomic Proyect
Making efforts trying to implement the Atomic Design System around the Frontend Development process.

## Concept

* http://atomicdesign.bradfrost.com/table-of-contents/

## Proyect Specs

* We need a Component System that can be handled starting from a static HTML, rather than a JS SPA Framework like others do.
* A system based on Atomic Components (Atoms, Molecules, Organisms, Templates, Pages).
* Components composed of jade, stylus and js(es6).
* That their view can be added through includes/mixins in jade.
* That their styles can be added through imports in stylus.
* That their scripts can be added through imports in js(es6).

## Ideas to compose

### Nº 1
* Create a page.jade, page.js(es6) and page.styl per view.
* Then include manually all the assets of the components on parallel.
* And Compile.

### Nº 2
* Just include the component view in the Page.
* Then with the help of a CLI, automatically bundle all the components .styl files, and .js files with their instance, into component.styl and component.js respectively.
* And Compile.

## Complements Specs
* A way to manage relationship between components.
* A way to handle actions between components https://goo.gl/KJNn2.
* A way to access to any component functionality, globally.
* A Grid System for styling.
