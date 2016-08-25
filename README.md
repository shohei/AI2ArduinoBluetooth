# AI2ArduinoBluetooth

## About
To control LED using Arduino-Android communication over Bluetooth.
The Android side is developed by MIT App Inventor 2(AI2).
The Arduino side uses bluetooth module(HC-06).

This is based on the article **Turning a LED on and off with an Arduino, a HC-06 and Android**.
[http://www.martyncurrey.com/turning-a-led-on-and-off-with-an-arduino-a-hc-06-and-android/](http://www.martyncurrey.com/turning-a-led-on-and-off-with-an-arduino-a-hc-06-and-android/)


## Modification from original
The code of for Arduino in the article was using SoftwareSerial, however, that did not work with my Arduino Mega 2560. What I changed is to replace SoftwareSerial to HardwareSerial2. This is how I've done:

```
#define BTserial Serial2
```





