## Objetivo
Modificar al programa sh.c para ejecutar al comando anterior

## Herramientas
git

make

gcc

## Conceptos
1) Como se crean nuevos procesos
+ Un programa padre (sh.c) ejecuta la llamada a sistema fork
+ La llamada a sistema fork clona al proceso padre
+ El proceso hijo manda a llamar a exec para ejecutar otro codigo

## Que aprendi
Aprendi como hacer un programa que ejecute el comando anterior, esto lo logramos guardando en un array los caracteres del ultimo comando ejecutado y reutilizarlo para hacer la llamada al sistema y se ejecute nuevamente. Hicimos uso del fork que basicamente lo que hace es clonar un proceso y el exex sirve para ejecutar un codigo.

## Url del commit
https://github.com/jorgant23/so-jorgeV/commit/844c66197c04226bef9721188b6f3a35dc1d1aa1?diff=split
