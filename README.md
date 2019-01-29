# UVR2MQTT
Auslesen des DL-Busses der UVR1611 mit einem ESP8266 (hier NodeMCU) und Weitergabe aller Temperatur- und Sensorwerte (alle 60 sec) per MQTT.


Der Anschluss an den DL-Bus der UVR1611 mit einem einfachen Spannungsteiler (keine galvanische Trennung!):


![Anschlusschema UVR1611 NodeMCU](https://github.com/futschikato/UVR2MQTT/raw/master/pic/uvr_nodemcu.png)


Output von MQTTfx:

![MQTTfx Output](https://github.com/futschikato/UVR2MQTT/raw/master/pic/mqttfx.png)
