# UVR2MQTT
Auslesen des DL-Busses der UVR1611 mit einem ESP8266 (hier NodeMCU) und Weitergabe aller Temperatur- und Sensorwerte (alle 60 sec) per MQTT.


Der Anschluss an den DL-Bus der UVR1611_

Da die Ausführung mit einem einfachen Spannungsteiler über längere Abstände gleiche Werte lieferte (obwohl diese sich änderten) und diese Version keine galvanische Trennung besitzt bin ich auf die Variante mit einem Optokoppler umgestiegen:


![Anschlusschema UVR1611 NodeMCU](https://github.com/futschikato/UVR2MQTT/raw/master/pic/uvr_optokoppler.png)


Output von MQTTfx:

![MQTTfx Output](https://github.com/futschikato/UVR2MQTT/raw/master/pic/mqttfx.png)
