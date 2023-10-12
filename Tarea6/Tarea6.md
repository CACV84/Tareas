## Programa de capacitacion
### Tarea 6

##### Patrones de diseño:

- Singleton
    Es un patrón de diseño creacional que garantiza que tan solo exista un objeto de su tipo y proporciona un único punto de acceso a él para cualquier otro código.

    El Singleton lo que hace es convertir el constructor en privado, de manera que nadie lo pueda instanciar. Entonces, si el constructor es privado, ¿cómo se instancia el objeto? Pues a través de un método público y estático de la clase. En este método se revisa si el objeto ha sido instanciado antes.
    
- Template
    Es un patrón de diseño de comportamiento que define el esqueleto de un algoritmo en la superclase pero permite que las subclases sobrescriban pasos del algoritmo sin cambiar su estructura.

- Strategy
    Es un patrón de diseño de comportamiento que te permite definir una familia de algoritmos, colocar cada uno de ellos en una clase separada y hacer sus objetos intercambiables.

    El patrón Strategy te permite aislar el código, los datos internos y las dependencias de varios algoritmos, del resto del código. Los diversos clientes obtienen una interfaz simple para ejecutar los algoritmos y cambiarlos durante el tiempo de ejecución.