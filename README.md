# Java_Clases

## Tarea 3

Uso y manipulación de objetos mediante operaciones sencillas, trabajando con métodos.
Uso de las clases CuentaBancaria, Dado y LocalTime para obtener una serie de resultados
Uso de IDE NetBeans.

La clase CuentaBancaria implementa un modelo simplificado de cuenta para gestionar saldos, descubiertos, ingresos, extracciones, transferencias, embargos.

### Restricciones

En el Ejercicio01 se llevan a cabo las siguientes acciones:
1. Declarar tres variables referencia a objetos instancia de la clase CuentaBancaria. 
2. Instanciar tres objetos de la clase CuentaBancaria a los cuales apuntarán cada una de las variables anteriores. Probar con errores para comprobar que funciona el lanzamiento de excepciones por parte de sus constructores:
3. Intentar crear una cuenta con fecha no válida (01/09/2027). Usar un bloque try-catch para capturar la excepción y gestionar ese error mostrando por pantalla el mensaje de error que te proporcione la excepción. 
4. Crear otra cuenta con un saldo no válido (-200.00 euros). Usar otro bloque try-catch para capturar la excepción que se pueda producir al invocar al constructor para evitar que tu programa "aborte". Mostrar el texto del error por pantalla.
5. Crear una cuenta válida con un saldo inicial de 1000.00 euros, con fecha de creación a 1 de julio de 2021 y -200.00 euros de límite de descubierto. Utilizar el constructor de tres parámetros. En este caso será la variable CuentaPrivada.
6. Crear una cuenta válida con un saldo inicial de 200.00 euros y con fecha de creación a 1 de julio de 2021, sin indicar nada más. Utilizar el constructor de dos parámetros
