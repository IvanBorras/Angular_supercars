# Sportcars




##  Configuración del Proyecto
- Inicializar un nuevo proyecto Angular utilizando la CLI.
- Organizar la estructura de carpetas de manera lógica y escalable, agrupando por funcionalidad.

##  Autenticación de Usuarios
- Implementar páginas de registro y login.
- Crear servicios de autenticación para comunicarse con las rutas /users del backend.
- Almacenar la sesión del usuario en las cookies para mantener la sesión activa.

##  Visualización y Reserva de Vehículos
- Permitir a todos los visitantes visualizar todos los vehículos disponibles en una página pública.
- Redirigir a los usuarios no autenticados a la página de login al intentar realizar una reserva.
- Completar el proceso de reserva para los usuarios autenticados.

##  Gestión de Vehículos y Reservas por Administradores
- Crear un apartado de administración accesible solo por usuarios con rol de administrador.
- Permitir a los administradores añadir, borrar, y actualizar vehículos, gestionar todas las reservas y usuarios.

##  Apartado Privado para Usuarios
- Crear un área privada donde los usuarios puedan ver sus propias reservas.
- Implementar funciones para que los usuarios puedan cancelar o modificar sus reservas.

##  Rutas y Navegación
- Configurar el enrutamiento de la aplicación para incluir rutas protegidas y rutas hijas.
- Implementar guardas de ruta para asegurar que solo los usuarios autenticados puedan realizar reservas y acceder a su apartado privado.
- Implementar guardas de ruta para que solo los administradores puedan acceder al apartado de administración.

## Interfaces TypeScript
Definir interfaces TypeScript.














































This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 17.2.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
