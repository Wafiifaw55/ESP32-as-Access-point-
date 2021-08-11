# ESP32-as-Access-point-
connecting with nod mcu Esp32 through WiFi using mobile phone, to control device
The ESP32 can act as a Wi-Fi station, as an access point, or both. In this project we’ll show you how to set the ESP32 as an access point using Arduino IDE.
When you set the ESP32 as an access point (hotspot), you can be connected to the ESP32 using any device with Wi-Fi capabilities without the need to connect to your router.
In simple words, when you set the ESP32 as an access point you create its own Wi-Fi network and nearby Wi-Fi devices (stations) can connect to it (like your smartphone or your computer).
There’s an add-on for the Arduino IDE that allows you to program the ESP32 using the Arduino IDE and its programming language. Follow this link to prepare your Arduino IDE: https://randomnerdtutorials.com/installing-the-esp32-board-in-arduino-ide-windows-instructions/
After you burn the code to Esp32 having the ESP32 running the new sketch, in your smartphone open your Wi-Fi settings and tap the:ESP32-Access-Point networkEnter the password you’ve defined earlier in the code:12345678
Open your web browser and type the IP address: 192.168.4.1. The web server page should load.
you will find two potton for two GBIO pin to turn on off, you can put in your cod isted of the LED to contrlo auther things like servo or relay etc.
I have share with you file for Arduino code, Fritzing schematic diagram.
I just use two LED with 1K ohm resistor and Nod Mcu ESP32 development board, all is show in png file.
