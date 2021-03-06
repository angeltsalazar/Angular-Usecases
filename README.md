# Angular casos de uso

Estas son mis notas relacionas al desarrollo de aplicaciones con Angular 2

## Elementos que componen el framework de Angular

- Lenguaje de programación: TypeScript
- Componentes, estos a su vez están formados por:

        - Una clase en TypeScript, para el manejo de datos y funcionalidad.
        - Un Template en HTML para el UI
        - Estilos para el componente, en CSS
- Dependency injection: Usar este patron de diseño como una buena práctica.
- Angular CLI: Usar esta herramienta para la creación y desarrollo de aplicaciones.
- Utilizar la librerías provistas por Angular, para Ruteo, Formas, HttpClient, Animaciones, PWA, entre otras.

Ver [Angular applications: The essentials](https://angular.io/guide/what-is-angular)

## Desarrollo de una aplicación

- Crear el proyecto para la aplicación usando una de las siguientes métodos: 
  - A través de un servicio en la nube. Como [StackBlitz](https://stackblitz.com/)
  - Usando Angular CLI.
- Crear la vista inicial con una lista de elementos
  - Crear el componente.
  - Crear el template de HTML, para el componente. (snippet: angularCreateList)
  - Crear el UI del componente utilizando HTML y los datos del componente.

Ver [Getting started with Angular](https://angular.io/start)