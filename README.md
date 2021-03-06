# Taller de introducción a la robótica

Este repositorio contiene archivos de apoyo para un taller de robótica con Arduino.

En el taller se monta y se programa un kit [Smart Car de Arduino](https://es.aliexpress.com/item/32795674146.html), que se controla por bluetooth con la app de Android [Arduino Bluetooth RC Car](https://play.google.com/store/apps/details?id=braulio.calle.bluetoothRCcontroller). 

- El documento **Taller de robótica.pdf** contiene las diapositivas explicativas del taller. 
- La carpeta **manuales** contiene los manuales del kit en PDF.
  - *4WD Bluetooth Hardware Installation Tutorial.pdf*: Manual de montaje del kit
  - *SPP-CA Bluetooth module AT commands.pdf*: Manual de comandos AT para configurar el módulo Bluetooth
  - *Wiring guide.pdf*: Tabla de guía rápida de conexión de los distintos módulos a los pines del controlador Arduino
- La carpeta **arduino** contiene los scripts y librerías necesarios para programar el kit
  - *bt_test*: script de test del módulo bluetooth
  - *display_test*: script de test de la pantalla LED de 7 segmentos
  - *motor_test*: script de test de movimiento del Smart Car
  - *sonar_test*: script de test del módulo sensor de distancia por ultrasonidos.  
    Muestra la distancia en el monitor serie.
  - *sonar_display_test*: script de test del módulo sensor de distancia por ultrasonidos.  
    Muestra la distancia en la pantalla LED.
  - *taller_robot*: script con el programa completo
  - *libraries*: Librerías utilizadas por los scripts
    - *DigitalTube*: Librería de control de displays de 7 segmentos TM1637 (by Fred.Chu)
    - *NewPing*: Librería de control de sensores de ultrasonidos HC-SR04 (by [Tim Eckel](https://bitbucket.org/teckel12/arduino-new-ping))

