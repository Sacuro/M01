# Reglas de las particiones

## MBR-DOS
Las reglas de las particiones de mbr son las siguientes: Solo pueden tener cuatro particiones primarias. Cada particion puede tener un máximo de 2TB (Haciendo que el máximo de capacidad aprovechable en un disco MBR sea de 8TB, puesto que el espacio sobrante se perdería) Puedes usar una de esas particiones primarias para convertirla en extended, y tener así N logicas. (Si tenemos un windows instalado nos obliga a tener una particion primaria activa, lo que nos limita aún más las particiones) 

## GPT
Puedes tener N particiones primarias a diferencia del MBR, supera el límite de 2TB por partición, y hasta el momento, no hace falta pensar en el límite, porque aún queda tiempo para ello.

## Por lo tanto, ¿Cual es mejor? 
La respuesta es obvia: siemrpe que podamos hemos de trabajar en el sistema de archivos GPT, porque nos ofrece más libertades y ventajas que el antiguo MBR.
