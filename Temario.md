Taller de desarrollo web
========================

Objetivo
--------

El participante asistirá al desarrollo de una aplicación MEAN.


Perfil del participante
-----------------------

- El participante deberá contar con experiencia previa en JavaScript de lo contrario se le dificultara el seguir los conceptos a tratar.
- El participante deberá contar con conocimientos básicos de uso de terminal (consola) ya que algunas de las sesiones harán uso de la misma.


Requisitos
----------

- Perfil de Google+ (Ya sea con cuenta de Gmail o de terceros)
- Cuenta de GitHub
- Cuenta de Heroku
- Conexión a Internet con suficiente velocidad para usar Google Hangouts
- Editor de código fuente (Sublime Text, Atom, Brackets, etc.)
- Node.js (ultima versión estable)
- MongoDB y Redis (puede ser local, maquina virtual local, maquina virtual remota, etc.)


Sesiones
--------

### Bases de desarrollo web

#### Objetivo

El participante comprenderá conceptos básicos de Internet.

#### Introducción

Aunque se trata de un tema básico, muchos no tienen las bases necesarias. Discutiremos de forma general los conceptos básicos en la infraestructura de una aplicación web relacionado.

#### Desarrollo

- Arquitectura cliente/servidor
- Dirección IP
- DNS, Nombres de dominio
- Servidor web
- HTTP (verbos, recursos, encabezados, códigos de respuesta, contenido)
- HTML, CSS, DOM
- AJAX, JSON
- Aplicación cliente vs aplicación servidor vs aplicación cliente/servidor

### Planeación del API

#### Objetivo

El participante conocerá la importancia de documentar los servicios antes de iniciar la programación de una aplicación.

#### Introducción

Antes de iniciar el desarrollo del cliente o del servidor definiremos que servicios se van a usar así como las respuestas de los mismos, de esta forma podemos trabajar independiente mente y facilitar la integración mas adelante.

#### Desarrollo

- REST, Servicios RESTful y Modelo de madurez de Richardson
- Markdown
- API Blueprint: [Apiary](http://docs.tdw1.apiary.io)

### Desarrollo del cliente con AngularJS (y compañía)

#### Objetivo

El participante asistirá al desarrollo del un cliente web.

#### Introducción

Armaremos el cliente iniciando con una carpeta vacía, conociendo AngularJS según progresemos. Al final tendremos el cliente completo y funcionando sin necesidad de haber trabajado en los servicios.

#### Desarrollo

- Introducción a la aplicación cliente
- Arrancando el proyecto: Grunt, Bower, Browserify
- Maquetado básico de la interfaz de usuario usando Bootstrap
- Definiciones básicas: Controller, Directive, Factory/Service
- Llamadas a servicios con $http
- Maquetado del servidor con $httpBackend
- Rutas y estados
- Registro y entrada del usuario
- Perfil de usuario, edición y eliminación de cuenta
- Interacción con otros usuarios
- Lista de posts
- Creación y eliminación de posts

### Desarrollo del servidor con ExpressJS (y compañía)

#### Objetivo

El participante asistirá al desarrollo de un API RESTful

#### Introducción

Usando la documentación de los servicios armaremos los mismos desde cero, conociendo las diferentes herramientas según tengamos progreso.

#### Desarrollo

- Intro. aplicación de servidor
- Bases de datos NoSQL
- JavaScript en el servidor: Node.js
- Módulos, NPM
- Http, Connect, ExpressJS
- Middleware
- Conectando con Mongo y Redis
- ABC Usuarios
- Autenticando a un usuario
- Interacciones entre usuarios
- ABC Posts
- Lista de posts

### Integración

#### Objetivo

El participante asistirá a la integración entre las aplicaciones cliente y servidor.

#### Introducción

Al llegar a este tema, debemos tener un cliente que funciona sin servicios y unos servicios completos, por lo que solo deberemos reemplazar el maquetado del API con la conexión real y todo deberá funcionar tal y como lo planeamos (si es que Murphy no decide jugar con nuestros planes).

#### Desarrollo

- Remover $httpBackend y probar la integración con los servicios

### Liberación

#### Objetivo

El participante apreciara el potencial de las herramientas en la nube para ejecución y liberación de aplicaciones.

#### Introducción

Una ves que tenemos todo funcionando en nuestro local, es hora de irnos a "producción" instalando la aplicación en un servidor publico; como seguramente necesitaremos hacer cambios para mejorar el código y la funcionalidad, haremos que la liberación del código se realice de forma automática.

#### Desarrollo

- Instalando en Heroku
- Automatizando las actualizaciones a Heroku
