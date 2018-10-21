# MBR
---
## Que es?  
El MBR (master boot record) es el primer sector de los discos de almacenamiento de datos, donde se almacena la información necesaria para el correcto funcionamiento del disco.
## ¿Para que sirve? 
Puede usarse para: 
* Para almacenar una tabla de particiones

* Para identificar un dispositivo de disco individual (Menos usado)

* Para arrancar el sistema operativo mediante bootstrap

## ¿Cuanto pesa? 
El total de sus partes pesa 512 bytes, repartidos en tres partes.


Parte | Peso
----------------- | -------------------
Gestor de arranque| 446 bytes
Tabla de particiones | 64 bytes 
Firma de la unidad | 2 bytes


## ¿Por que es tan importante?

Sin él, el ordenador no podría arrancar debido a que no tiene un gestor de arranque, y no funcionaría.  (A no ser que utilizes un GNU GRUB, proveniente de Linux) 

---
>Fuentes: [Wikipedia](https://es.wikipedia.org/wiki/Registro_de_arranque_principal)  
