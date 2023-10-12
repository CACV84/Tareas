## Programa de capacitacion
### Tarea 7

##### Patron de diseño Singleton:

- Singleton
    
Todas las implementaciones del patrón Singleton tienen estos dos pasos en común:

Hacer privado el constructor por defecto para evitar que otros objetos utilicen el operador new con la clase Singleton.

Crear un método de creación estático que actúe como constructor. Tras bambalinas, este método invoca al constructor privado para crear un objeto y lo guarda en un campo estático. Las siguientes llamadas a este método devuelven el objeto almacenado en caché.

![](/Tarea7/imagenes/Singleton.png)

Si tu código tiene acceso a la clase Singleton, podrá invocar su método estático. De esta manera, cada vez que se invoque este método, siempre se devolverá el mismo objeto.

![](/Tarea7/imagenes/Cliente.png)