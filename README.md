# Taller de desarrollo web

Taller de desarrollo web enfocado a **programadores web con experiencia previa en JavaScript** y algún otro lenguaje de programación para servidor.

El taller consistirá de varias sesiones (por definirse) mediante Google Hangouts, aproximadamente 2 por semana, 1 a 2 horas por sesión. El cupo estara limitado a 8 personas y tendra costo (por definirse).

Las sesiones se desarrollaran de una manera informal, iniciando con algo de teoria sobre los temas a tratar seguidos por la practica en vivo; sesiones de preguntas y respuestas se daran segun sean necesarias, si es necesario dedicar una sesión completa a preguntas y respuestas asi se hara.

Durante el taller estaremos haciendo uso de muchas herramientas, por lo que los asistentes deberan tener flexibilidad e iniciativa para aprenderlas por su cuenta; algunas de las herramientas a usar son editor de cogido, linea de comando, Git, GitHub, Node.js, Grunt, Browserify, AngularJS, MongoDB (o Redis), Heroku, Codeship, y otras mas, segun sea necesario.

## Que vamos a construir?

Al final del curso tendremos una micro red social.

## Bases de desarrollo web

Aunque se trata de un tema básico, muchos no tienen las bases suficientes para comprender gran parte del desarrollo web. Tocaremos los siguientes temas de forma muy general y breve, salvo que se necesite explicar alguno a mas detalle.

- Arquitectura cliente/servidor
- Dirección IP
- DNS, Nombres de dominio
- Servidor web
- HTTP (verbos, recursos, encabezados, códigos de respuesta, contenido)
- HTML, CSS, DOM
- AJAX, JSON
- Aplicación cliente vs aplicación servidor vs aplicación cliente/servidor

## Planeación del API

Antes de iniciar el desarrollo del cliente o del servidor definiremos que servicios se van a usar asi como las respuestas de los mismos, de esta forma podemos trabajar independiente mente y facilitar la integración mas adelante.

- REST, Servicios RESTful y Modelo de madurez de Richardson
- Markdown
- API Blueprint: Apiary

## Desarrollo del cliente con AngularJS (y compañía)

Armaremos el cliente iniciando con una carpeta vacía, conociendo AngularJS segun progresemos. Al final tendremos el cliente completo y funcionando sin necesidad de haber trabajado en los servicios.

- Intro. aplicación de cliente
- Arrancando el proyecto: Grunt, Bower, Browserify
- Controller, Directive, Factory/Service
- Rutas y estados
- Llamadas a servicios con $http
- Imitando al servidor con $httpBackend

## Desarrollo del servidor con ExpressJS (y compañía)

Usando la documentación de los servicios armaremos los mismos desde cero, conociendo las diferentes herramientas segun tengamos progreso.

- Intro. aplicación de servidor
- JavaScript en el servidor: Node.js
- Módulos, NPM
- Http, Connect, ExpressJS
- Middleware
- API: CRUD

## Integración

Al llegar a este tema, debemos tener un cliente que funciona sin servicios y unos servicios completos, por lo que solo deberemos realizar la conexion del cliente y todo funcionara tal y como lo planeamos (si es que Murphy no decide jugar con nuestros planes).

- Reemplazando $httpBackend con el API real

## Vámonos a producción!

Una ves que tenemos todo funcionando en nuestro local, es hora de irnos a "producción" instalando la aplicación en un servidor publico; como seguramente necesitaremos hacer cambios para mejorar el código y la funcionalidad, haremos que la liberación del código se realice de forma automática.

- Instalando en Heroku
- Automatizando las actualizaciones a Heroku
