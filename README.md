# Arduino-2-Leds-Sincronizadas
Segunda práctica de 6 aprendiendo a usar Arduinos.

# Práctica 2

<b>Ejercicio 2: 3 Leds consecutivas</b>

En el siguiente ejercicio seguimos con nuestras pruebas con LED, en esta ocasión, procedemos a incluir 2 luces LED más y a coordinarlas entre si.

El <a href="https://github.com/Pachecards/Arduino-2-Leds-Sincronizadas/blob/master/CodigoPrueba">código</a> resultó no ser mucho más complejo que el del primer ejercicio, así que volvimos a usar <a href="https://www.tinkercad.com/">Tinkerkad</a> para diseñar el nuevo sistema con una configuración muy básica, pero funcional.

<center>
    <img src="https://raw.githubusercontent.com/Pachecards/Arduino-2-Leds-Sincronizadas/master/ArduinoEx2Circuito.png" height = 350 weight = 350>
</center>

Una vez con el diseño en nuestras manos, lo aplicamos a nivel físico, usando 3 Leds, 3 cables Macho-Hembra, 1 Arudino-UNO y 1 cable de electricidad.

La instalación estaba hecha, pero nos faltaba parte del código para que funcionara, buscando en internet nos encontramos una página que nos permitió que funcionaran en <a href="https://github.com/Pachecards/Arduino-2-Leds-Sincronizadas/blob/master/CodigoModificado1">la secuencia deseada</a>. (<a href="https://github.com/Pachecards/Arduino-2-Leds-Sincronizadas/blob/master/ArduinoUnoEx2VideoB%C3%A1sico.mp4">Video</a>)

Una vez que acabamos la primera parte del código, lo <a href="https://github.com/Pachecards/Arduino-2-Leds-Sincronizadas/blob/master/CodigoModificado2">modificamos</a> un poco para que las Leds se encendieran parpadeando en intervalos temporales pequeños, no nos costó mucho más de unos minutos. (<a href="https://github.com/Pachecards/Arduino-2-Leds-Sincronizadas/blob/master/ArduinoUnoEx2Plus.mp4">Video</a>)

Por último, conseguimos que los Leds parpadearn de forma irregular, haciendo que se encendiera uno solo al principio y después los otros dos que faltaban. El código usado es el <a href="https://github.com/Pachecards/Arduino-2-Leds-Sincronizadas/blob/master/CodigoModificado3">siguiente</a>. (<a href="https://github.com/Pachecards/Arduino-2-Leds-Sincronizadas/blob/master/ArduinoUnoEx2VideoSecuencial.mp4">Video</a>)