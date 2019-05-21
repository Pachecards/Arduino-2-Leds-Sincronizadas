# Arduino-2-Leds-Sincronizadas
Segunda práctica de 6 aprendiendo a usar Arduinos.

# Práctica 2

Ejercicio 2: 3 Leds consecutivas

En el siguiente ejercicio seguimos con nuestras pruebas con LED, en esta ocasión, procedemos a incluir 2 luces LED más y a coordinarlas
entre si.

El código resultó no ser mucho más complejo que el del primer ejercicio, así que volvimos a usar Tinkerkad para diseñar el nuevo sistema con una configuración muy básica, pero funcional.

Una vez con el diseño en nuestras manos, lo aplicamos a nivel físico, usando 3 Leds, 3 cables Macho-Hembra, 1 Arudino-UNO y 1 cable de electricidad.

La instalación estaba hecha, pero nos faltaba parte del código para que funcionara, buscando en internet nos encontramos una página que nos permitió que funcionaran en la secuencia deseada, se puede encontrar como ArduinoUnoEx2Faster.ino.

Una vez que acabamos la primera parte del código, lo modificamos un poco para que las Leds se encendieran parpadeando en intervalos temporales pequeños, no nos costó mucho más de unos minutos.

Por último, conseguimos que los Leds parpadearn de forma irregular, haciendo que se encendiera uno solo al principio y después los otros dos que faltaban. El código usado es el siguiente.
