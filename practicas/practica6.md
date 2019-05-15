# Objetivo:
Investigar y practicar sobre hilos.

# Herramientas:
gcc
git

# Conceptos:
+ Hilos:
  + Proceso ligero.
  + Solo tiene un stack y el codigo y el heap lo comparte con el proceso principal.
  + Si el proceso princpal termina, los hilos terminan.

+ Lock:
  + Mecanismo de sincronizacion.
  + Variable global que soporta dos operaciones:
    + lock, el primer hilo que hace lock se adueña del lock, el resto queda esperando.
    + unlock, el hilo dueño del lock lo libera.
  + Ayuda para resolver el problema de la seccion critica.
  
 + Semaforos:
    + Mecanismo de sincronizacion.
    + Variable global que tiene un valor inicial mayor o igual a cero. Soporta dos operaciones.
      + Wait/decrease. Si es mayor a 0 decrementa y continua, si es igual a 0 se suspende.
      + post/increase. Incrementa el valor del semaforo en uno.
    + Para asignar recursos
  + Problemas de sincronizacion.
    + Condicion de carrera. Ocurre cuando el resultado depende del orden en que se ejecutan los hilos.
    + Deadlock: Cuando dos o mas hilos estan esperando por un recurso que no se libera.
    + Productor/Consumidor: Ocurre cuando los datos se pueden sobre escribir.
    
   # Que aprendi:
   Aprendi sobre lo que son los hilos, procesos ligeros que requieren menos recursos que los procesos. Ademas pude entender otros            mecanismos  como los semaforos que sirven para sincronizacion al usar recursos.
   
   # URL del commit:
    https://github.com/jorgant23/so-jorgeV/commit/d1a311d3afbbe52800ca419498a522875b583766
