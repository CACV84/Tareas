## Programa de capacitacion
### Tarea 17

#### Tecnología JWT

#####  Definición y estructura

- Es un estándar, se define como un mecanismo para poder propagar entre dos partes, y de forma segura, la identidad de un determinado usuario, además con una serie de claims o privilegios. Estos privilegios están codificados en objetos de tipo JSON, que se incrustan dentro de del payload o cuerpo de un mensaje que va firmado digitalmente (va verificada).

- La firma del token (firma) está compuesta por la codificación del encabezado y el payload más una clave secreta y es generada por el algoritmo especificado en el encabezado. El resultado son tres cadenas separadas por puntos que se pueden usar fácilmente en entornos HTML y protocolos HTTP
- Header: encabezado dónde se indica, al menos, el algoritmo y el tipo de token, por ejemplo el algoritmo HS256 y un token JWT.
- Payload: donde aparecen los datos de usuario y privilegios, así como toda la información que queramos añadir, todos los datos que creamos convenientes.
- Signature: una firma que nos permite verificar si el token es válido



