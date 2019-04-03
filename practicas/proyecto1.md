## Objetivo
### Parte 1: Modifica el kernel de xv6 para que imprima cada vez que una llamada a sistema se emplee se imprima una línea con el nombre de la llamada a sistema y su número.
Pistas:
Modificar la función syscall() en syscall.c para antes de ejecutar la función imprimir, tener un arreglo con los nombres de las funciones.

### Parte 2: Agregar otra llamada a sistema (date) a xv6 que consulte el reloj de la computadora y devuelva el tiempo en formato UTC.
Pistas:
Utilizar la función cmostime() (definida en lapic.c) para obtener el valor de la hora actual. En el archivo date.h está definida la estructura usada por esa función.

## Herramientas
* git
* qemu
* xv6
* gcc

## Conceptos
* Llamadas a sistema
* Aplicacines de sistema
* Codigo fuente

## Que aprendi

## URL del commit:
Parte 1: https://github.com/jorgant23/so-jorgeV/commit/4a612b14faa3cda023927adffd22da0e113da8fb
Parte 2: https://github.com/jorgant23/so-jorgeV/commit/c6a4199be8a658c9935b611f349f0ae937d170d8
