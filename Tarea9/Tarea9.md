## Programa de capacitacion
### Tarea 9

#### Microservicios

##### Servicio REST

- REST (REpresentational State Transfer) son servicios que reciben las peticiones por el protocolo HTTP el cual se usa para ver cualquier página en un navegador web.
Los servicios REST permiten acceder y/o modificar la información mediante los métodos HTTP, por lo cual se puede acceder a ellos mediante URLs. Por lo general regresan la información en formato JSON, aunque también pueden regresar archivos XML o csv.

##### Elementos de un servicio REST

- métodos básicos de HTTP:
Post: Para crear recursos nuevos.
Get: Para obtener un listado o un recurso en concreto.
Put: Para modificar.
Patch: Para modificar un recurso que no es un recurso de un dato, por ejemplo.
Delete: Para borrar un recurso, un dato por ejemplo de nuestra base de datos.

- Archivos JSON
Los archivos JSON (JavaScript Object Notation) son archivos de texto para intercambiar información. Los archivos JSON están formados por una clave y un valor o un arreglo de propiedades.

- Status Codes (Códigos de Estatus)
Los servicios REST manejan Códigos de Estatus para indicar empiezan con:
200: la acción se realizó correctamente (Succesful)
300: se ha tenido que tomar una acción adiconal(Redirección)
400: Se esta enviando mal la información al servicio (Errores del cliente)
500: el error es de parte del servidor o de quien crea el servicio (Errores del servidor)

- Interfaz uniforme
 Ella indica que el servidor transfiere información en un formato estándar. El recurso formateado se denomina representación en REST. Este formato puede ser diferente de la representación interna del recurso en la aplicación del servidor. Por ejemplo, el servidor puede almacenar los datos como texto, pero enviarlos en un formato de representación HTML.

- Tecnología sin estado
En la arquitectura de REST, la tecnología sin estado se refiere a un método de comunicación en el cual el servidor completa todas las solicitudes del cliente independientemente de todas las solicitudes anteriores. Los clientes pueden solicitar recursos en cualquier orden, y todas las solicitudes son sin estado o están aisladas del resto. Esta limitación del diseño de la API REST implica que el servidor puede comprender y cumplir por completo la solicitud todas las veces. 

- Sistema por capas
En una arquitectura de sistema por capas, el cliente puede conectarse con otros intermediarios autorizados entre el cliente y el servidor y todavía recibirá respuestas del servidor. Los servidores también pueden pasar las solicitudes a otros servidores.

- Almacenamiento en caché
Los servicios web RESTful admiten el almacenamiento en caché, que es el proceso de almacenar algunas respuestas en la memoria caché del cliente o de un intermediario para mejorar el tiempo de respuesta del servidor.

- Código bajo demanda
En el estilo de arquitectura de REST, los servidores pueden extender o personalizar temporalmente la funcionalidad del cliente transfiriendo a este el código de programación del software. Por ejemplo, cuando completa un formulario de inscripción en cualquier sitio web, su navegador resalta de inmediato cualquier error que usted comete, como un número de teléfono incorrecto. El navegador puede hacer esto gracias al código enviado por el servidor.
