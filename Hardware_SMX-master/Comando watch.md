# ¿Que es?
Es un comando que nos permite automatizar acciones para que se ejecuten de forma periódica. Suele usarse para obtener datos en pantalla cada cierto tiempo determinado. 
Uno de los ejemplos de uso es ver cuanta memoria está utilizando nuestro sistema, el comando sería: 
<pre> watch free -m </pre>

Si quisieramos que el comando **se ejecutase cada tiempo que nosotros decidamos** (en este caso 3 segundos) sería así: 
<pre> watch -n 3 free -m </pre>
**El tres debe ser substituido por el número que deseamos, siendo numerado en segundos**
>[Fuente](https://www.linuxadictos.com/ejecutar-un-comando-linux-cada-cierto-tiempo-con-watch.html)
