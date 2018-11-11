# Para que sirven Ctrl+z y bg?
## Ctrl+z
Ctrl+z sirve para congelar un proceso que tengamos abierto desde el terminal. 
Ejemplo: hemos abierto el gparted desde terminal y queremos usar el terminal, pero no podemos porque gparted está aún abierto. 
EN este caso, al pulsar "**ctrl+z**" nos aparecerá el siguiente mensaje: 

[![Image from Gyazo](https://i.gyazo.com/5270feaf0b090686832c85bd7f73a0d1.png)](https://gyazo.com/5270feaf0b090686832c85bd7f73a0d1)

Ahora tenemos el proceso "congelado" y nos permitirá seguir utilizando el terminal. Cuando queramos volver a usar el programa, al final del nombre del programa (en este caso gparted) pondremos un espacio y &, quedando así: 
<pre> gparted & </pre>
Bg es un comando que nos indica cuantos procesos hay en el background, es decir, en segundo plano. 
