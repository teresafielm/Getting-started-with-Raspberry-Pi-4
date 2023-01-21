# Getting-started-with-Raspberry-Pi-4
Repositorio que explica cómo realizar la puesta en marcha de una raspberry pi 4

Se elabora la presente actividad para poder verificar la conexión de nuestro Raspberry Pi 4 (Comunicación con ssh)

Para la instalación de Raspberry Pi 4

Se necesita instalar un sistema operativo dentro de una tarjeta SD para poder funcionar con Linux, esto se hace a partir de un Imager, el cual copia el sistema operativo (1GB) a una tarjeta SD. Se debe seleccionar el puerto donde se encuentre nuestra tarjeta y escribir en él. Al abrir el imager:

Seleccionar RaspberryPi OS 32bits y realizar Ctrl+Shift+X para tener una configuración estándar, esto se realiza utilizando raspbian.

Seleccionar tarjeta MicroSD -Insertar la tarjeta en el adaptador -Insertar el adaptador -Seleccionar unidad

Configuraciones -Enable SSH -Username pi -Password: **** -Configure Wireless LAN

En dado caso que no lo hagas por el metodo ssh, este son sus configuracion default
Default Password: raspberry
Defalut User: pi
Por ultimo hacer Click en write.

Sacamos la tarjeta microSD y la ponemos en la Raspberry Pi 4

Posteriormente: 

-Energizamos 
-Conectamos puerto HDMI, teclado y mouse
-Obtener la IP de la Raspberry Pi 
-Conectarse por SSH de la siguiente manera:

ssh pi@192.168.x.x

Y listo; Comunicacion-por-ssh.png

Estaremos conectados.
