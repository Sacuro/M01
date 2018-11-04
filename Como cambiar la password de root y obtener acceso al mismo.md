# No tengo la contraseña de root, ¿es el fin del mundo? 
No, no es el fin del mundo, hay varias maneras de obtener permisos de root sin conocer la contraseña, pero en este caso vamos a daros la posibilidad de además cambiarla, para que no se os vuelva a olvidar. 

## Primer método 
El primer metodo es sencillo, hemos de poner en el terminal: <pre> sudo su </pre>
Ahora con el acceso a los permisos de root, vamos a cambiar la contraseña con el siguiente comando: 
<pre> passwd root </pre>
Pondremos la contraseña una vez, y seguidamente una vez más para cambiarla. Una vez hecho esto, nuestra contraseña de root habrá sido modificada. 

## Segundo método
El segundo método es igual de sencillo que el anterior, pero antes de todo vamos a cambiar la contraseña de root, y después accederemos con la nueva contraseña que hayamos elegido. Primero de todo pondremos el comando <pre> sudo passwd root </pre> 
Ahora, cambiaremos la contraseña poniendola primero una vez y después otra para guardar los cambios. Una vez hecho esto escribiremos el comando <pre> su - </pre>
Cuando escribamos ese comando, nos pedirá la contraseña del usuario root, y como la acabamos de cambiar, sabemos cual es y la ponemos. Aunque al poner la contraseña no escriba nada **si está escribiendo, solo que no se ve para mayor seguridad**, una vez escrita pulsaremos enter y ya tendremos acceso root.
