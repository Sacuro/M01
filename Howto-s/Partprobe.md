# Partprobe

Partprobe es un comando de linux usado para avisar al sistema operativo de los cambios en la tabla de las particiones del sistema. 

Este comando nos permite informar al kernel del sistema operativo sobre los cambios en laa tabla de particiones. Lo que hace es pedirle al sistema operativo que se relea la tabla de particiones. 

Un uso práctico del comando es usarlo después de utilizar Fdisk o GParted para que el sistema operativo reconozca la nueva configuración de la tabla de particiones. 

## Extensiones útiles del comando 

partprobe -s: Nos muestra un resumen de los dispositivos y las particiones del sistema. 

partprobe -h: Nos muestra las opciones que nos ofrece el comando. 
