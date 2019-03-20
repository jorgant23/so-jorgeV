# Objetivo
Modificar al programa init para que muestre un programa de bienvenida.

# Herramientas
gcc

make

git

# Conceptos

1)Proceso
+ Instancia de un programa.
+ Tiene tres partes:
++ Stack: variables y las llamadas a funciones.
++ Heap: memoria dinámica (malloc o new)
++ código

+ Se crea mediante dos llamadas a sistema:
++ Fork clona
++ exec cambia el código

+ Tiene un estado:
++ Corriendo
++ Durmiendo (Listo)
++ Espera
++ Completado
++ Zombie

2) Programa init
+ Es el programa encargado de inicializar al SO para dejarlo listo para usarse
+ Es el unico proceso que crea el SO

# Que aprendi
Aprendi como los programas tienen varios estados de acuerdo a su lugar en la ejecucion, puede estar corriendo, durmiendo, en espera, completado o zombie. Tambien aprendi como el SO hace uso deun stack que va guardando las variables que se usan en el proceso y una vez que sales de una funcion las deshecha.

# Url del commit
https://github.com/jorgant23/so-jorgeV/commit/bd5fec206949bca48356061556ff37d69f370bd4
