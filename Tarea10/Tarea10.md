## Programa de capacitacion
### Tarea 10

#### Microservicios

#####  Spring Boot

- Java Spring Boot (Spring Boot) es una herramienta que hace que el desarrollo de aplicaciones web y microservicios con Spring Framework sea más rápido y fácil a través de tres funcionalidades principales:

    1.- Configuración automática
    2.- Un enfoque obstinado de la configuración
    3.- La capacidad de crear aplicaciones independientes

##### Controlador

- Dentro de la descripción de los componentes del modelo MVC (Patrón MVC), este componente es el que responde a la interacción (eventos) que hace el usuario en la interfaz y realiza las peticiones al modelo para pasar estos a la vista.

- Responde a eventos (acciones del usuario) e invoca peticiones al ‘modelo’ cuando se hace alguna solicitud sobre la información. También puede enviar comandos a su ‘vista’ asociada si se solicita, por lo tanto se podría decir que el ‘controlador’ hace de intermediario entre la ‘vista’ y el ‘modelo’.

#####  Servicio REST

- REST (REpresentational State Transfer) son servicios que reciben las peticiones por el protocolo HTTP el cual se usa para ver cualquier página en un navegador web. Los servicios REST permiten acceder y/o modificar la información mediante los métodos HTTP, por lo cual se puede acceder a ellos mediante URLs. Por lo general regresan la información en formato JSON, aunque también pueden regresar archivos XML o csv.

- Características:
- Las API REST son independientes de la tecnología que se utiliza. Puede escribir aplicaciones del lado del cliente y del servidor en diversos lenguajes de programación, sin afectar el diseño de la API.
- Se configura lo que se conoce como protocolo cliente-caché-servidor sin estado: existe la posibilidad de definir algunas respuestas a peticiones HTTP concretas como cacheables, con el objetivo de que el cliente pueda ejecutar en un futuro la misma respuesta para peticiones idénticas.
- Sin estado: Los Servicios REST pueden ser escalados hasta alcanzar grandes rendimientos para abarcar la demanda de todos los posibles clientes.
- Cliente-Servidor: Los servicios REST deben estar basados en una arquitectura Cliente-Servidor. Un servidor que contiene los recursos y estados de los mismos, y unos clientes que acceden a ellos.
- Información cacheable: Para mejorar la eficiencia en el tráfico de red, las respuestas del servidor deben tener la posibilidad de ser marcadas como cacheables. Esta información es utilizada por los clientes REST para decidir si hacer una copia local del recurso con la fecha y hora del último cambio de estado del recurso.
- Interfaz uniforme: Una de las características principales de los servicios Web REST es el uso explícito de métodos HTTP (HyperText Transfer Protocol). Estos métodos son indicados en la cabecera HTTP por parte del cliente y son los siguientes:
• GET: recoge información de un recurso
• PUT: modifica o actualiza el estado de un recurso
• POST: crea un nuevo recurso en el servidor
• DELETE: elimina un recurso del servidor.

- Acceso a recursos por nombre:Un sistema REST está compuesto por recursos que son accedidos mediante URL, y éstas deben ser intuitivas, predecibles y fáciles de entender y componer. 
- Recursos relacionados: Los recursos accesibles en el servidor suelen estar relacionados unos con otros. Por tanto, la información de estado de un recurso debería permitir acceder a otros recursos.
- Respuesta en un formato conocido: La representación de un recurso refleja el estado actual del mismo y sus atributos en el instante en el que el cliente ha realizado la solicitud. Este resultado puede representar simplemente el valor de una variable en un instante de tiempo, un registro de una Base de Datos o cualquier otro tipo de información. 