# Control de inversor #

Este proyecto, utilizando la librería de SSUI, demuestra el diseño y creación de un inversor con Raspberry Pi, para la carrera de Ingeniería Mecatrónica del Instituto Tecnológico de Celaya.

Este código se utiliza en una tarjeta Raspberry Pi, pero puede funcionar en tarjetas compatibles como Banan Pi o BeagleBoneBlack. Se recomienda utilizar una distribución de Linux basada en Debian para facilitar la instalación de dependencias y librerías.

### Video de demostración ###
<div style="text-align:center">[![Video](http://img.youtube.com/vi/GauLbHVjNHk/0.jpg)](http://www.youtube.com/watch?v=GauLbHVjNHk)</div>

### Funciones ###

* Generación de SPWM 0 - 200 hz
* Temporizador en segundos
* Configuración guardada en archivo .ini
* Multiplataforma: Windows, Linux, Mac (no probado en Mac).
* Rango de frecuencia interna 1 hz - 20 Khz.
* Interfaz gráfica completamente configurable mediante YAML.
* Interfaz accesible por teclado, ratón, joystick o teclado matricial.
* Capacidad de ser controlado por LabVIEW o remotamente por SSH

### Liberías y dependencias utilizadas ###

* Python 2.7+
* Pygame
* pigpio
* GPIO Rpi
* GNU Screen

Para su uso, instalar todas las dependencias, clonar este repositorio y correr main.py con privilegios de root. Configure una conexión SSH si desea utilizar este protocolo (https://www.raspberrypi.org/documentation/remote-access/ssh/).

### Licencia ###

MIT
