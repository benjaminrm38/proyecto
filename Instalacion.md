# Instalaccion:
Esta instalacion sera enfocada en la **maxima optimizacion de la raspberry**

## Las principales SO de Raspberrys
Raspbian, es el sistema operativo oficial. Una distribución que funciona muy bien para una gran variedad de usos. Puedes descargarlo [desde la web oficial de Raspberry Pi](https://www.raspberrypi.com/software/)

NOOBS y NOOBS Lite son dos muy buenas opciones para principiantes en el uso de la Raspberry Pi. Aún así, puede dar mucho juego, así que es interesante conocerlo también. Se puede descargar [desde la web de Raspberry Pi](https://www.raspberrypi.com/software/)

Retroarch una muy buena distribución si lo que quieres es convertir la Raspberry Pi en un emulador de consolas retro. Puedes descargar [aquí](http://www.lakka.tv/get/)


## WINDOWS 
1. Descargar e instalar la aplicación para instalar el SO en la Raspberry. En este caso es BerryBoot. [BerryBoot](https://www.berryterminal.com/doku.php/berryboot)
2. Ejecuta la app. Seleccione la unidad donde se instalará el SO.
3. Seleccion el SO a instalar.
Ya podríamos introducir la tarjeta en la Raspberry

## Linux

En cambio Linux a diferencia de los demas se descarga a traves de comandos
Instalamos sus dependencias
> sudo apt-get install -y pv curl python-pip unzip

> sudo pip install awscli

> uname -s

 Si el comando nos devuelve _Linux_...
 Ahora lo que devuelva se tiene que subsituir por PEPE en estos comandos
 
> wget https://raw.githubusercontent.com/hypriot/flash/master/PEPE/flash
chmod +x flash

ahora lo movemos

> sudo mv flash /usr/local/bin/flash

Y ya tenemos el sistema operativo que queramos

## VARIOS SO EN UNA RASPBERRY PI
**Para lograr esto sólo tendrías que recurrir a NOOBS o BerryBoot**
Extraer el archivo y copia todo en una tarjeta SD **FORMATEADA**
Ahora reinicia la RASPEBRRY
Ve al menu y selecciona el o los sistemas que quieras instalar
![450_1000](https://user-images.githubusercontent.com/72190320/142776416-387e1adf-985c-419f-8de3-ec45ebbb28d6.jpg)

Una vez hecho esto podras arrancar con cualquier sistema operativo

