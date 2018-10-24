# MBR Y GPT

Reglas de las particiones
MBR
las reglas de las particiones de mbr son las siguientes: Solo pueden tener cuatro particiones primarias. Cada particion puede tener un máximo de 2TB (Haciendo que el máximo de capacidad aprovechable en un disco MBR sea de 8TB, puesto que el espacio sobrante se perdería) Puedes usar una de esas particiones primarias para convertirla en extended, y tener así N logicas

GPT
Puedes tener N particiones primarias A diferencia del MBR, supera el límite de 2TB por partición, y hasta el momento, no hace falta pensar en el límite, porque aún queda tiempo para ello.
