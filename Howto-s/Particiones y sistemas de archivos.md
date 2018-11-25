# ¿Que es un sistema de archivos? 

Un sistema de archivos es el formato que le damos a una partición, para poder ordenar, clasificar y asignar a nuestross archivos el espacio que necesiten. 
Cabe decir que cada sistema de archivos tiene sus propias ventajas y desventajas, así que es importante conocerlos para elegir el que mejor se ajusta a nuestras necesidades.

[![Image from Gyazo](https://i.gyazo.com/f0b216e703267d876f44f4a976de77dc.png)](https://gyazo.com/f0b216e703267d876f44f4a976de77dc)

## Tipos de sistemas de arhivos 

Fat 32: Admite únicamente archivos de no más de 4GB
ExFat: Es el sistema de archivos creado para solucionar el problema de FAT 32
NTFS: Con más seguridad que los sistemas de archivos FAT, permite además archivos de más de 4GB

# ¿Que es una partición?

Una partición es un espacio seleccionado dentro de una unidad de almacenamiento. Es decir, es *particionar* el disco duro en varias partes para así poder separar el espacio, para poder ser ordenado según el sistema de archivos a usar. 

[![Image from Gyazo](https://i.gyazo.com/4c4ddca998cd75cbaa6f00737cfd7ae1.png)](https://gyazo.com/4c4ddca998cd75cbaa6f00737cfd7ae1)

## Comandos 

**Partprobe**: Nos permite leer el disco y reconocer las particiones paraa asegurarnos de haberlas hecho bien. 

**Kpartx -a "nombredeldisco"**: De esta forma nos quedará guardado en el **mapper** y podremos observar si lo hemos hecho bien con: ls "disco"/mapper/"disco"

**a**: Para colocar una particion como un punto de montaje

**n**: Para crear una partición

**l**: Para crear una partición lógica

**p**: Para crear una partición primaria

**e**: Para crear una partición extended

**t**: Para cambiar el sistema de archivos de la partición

**82**: Para convertirla a swap

**7**: Para convertirla a ntfs
