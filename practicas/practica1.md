## Objetivo
Crear dos llamadas a sistema una para apagar y otra para reiniciar. 
Y crear sus respectivos programas.

## Herramientas
git

make 

gcc

## Conceptos
1) Llamadas a sistema
+ La forma que el kernel (SO) da acceso al HW
+ Se implementa mediante interrupciones de software (trap), ie,
la aplicación se interrumpe para que el kernel se ejecute.

2) Modo kernel
+ Es bit/registro que activa el CPU para acceder al HW
+ Solo hay un programa que se ejecuta con este bit, es el kernel

3) Interrupciones
+ Es la forma que el HW interactua con el CPU

## Que aprendi:
Aprendia utilizar llamadas a sistema para crear mis funciones de apagar y reiniciar, esto lo hice mediante interrupciones de software (traps). En esta práctica pude reforzar los conocimientos de git para hacer mi commit y manejar las versiones de mis archivos. Utilicé direcciones en hexadecimal e instrucciones en ensamblador para crear mis funciones de apagar y reiniciar.

## Url del commit:
https://github.com/jorgant23/so-jorgeV/commit/7eba83b491300948fcfdbe463bacd30e0e988b03
