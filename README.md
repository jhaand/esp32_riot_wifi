# esp32_riot_wifi
A small example program networking via wifi on the ESP32 using RIOT-OS with lwIP

The nice thing about the ESP32 and ESP8266 remains that you have very
easy way to access the network via wifi for a microcontroller. RIOT-OS
also allow you to do this but I found it quite hard to find information
on it. 

Thanks to some tweets with Alexandre Abadie
([https://twitter.com/alexandreabadie/status/1375854536158556167]) I
found out that the ```RIOT/example/paho-mqtt``` program can use the wifi
module from the ESP32. It uses lwIP to create a network socket and will
connect to an MQTT bridge. 

This example will show you how to create activate the wifi and get a
reaction back if you connect to it. 

# More information

RIOT documentation on ESP32

Get RIOT to compile for ESP32

The paho-mqtt examplem. 

