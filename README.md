# CTC-GSi-8---Homeassistant
For connection between CTC GSi and Homeassistant (testet with GSi 8 and GSi 16)It probably works on EcoHeat 400 series as well

![Skærmbillede 2022-11-07 151830](https://user-images.githubusercontent.com/71944008/200332690-383c7424-a406-4df4-b542-bcc13bf7fdfd.png)


RJ12 cable cut in half an connected to NodeMCU ESP32

Pinout for the RJ12 cable connected to the display of the CTC heat pump

![image-png-Jun-29-2022-09-29-07-52-AM](https://user-images.githubusercontent.com/71944008/200332214-63fd21a7-54ce-4be7-8b95-4aae05a2bc62.png)

1: GND
2: 5V
3: TX GPIO 17
4: RX GPIO 16
5: Flow control pin 
6: Not used

![nodemcu-esp32-iot-mainboard](https://user-images.githubusercontent.com/71944008/200329565-8957985a-914a-461c-9d2f-196335280dca.jpg)

Using Esphome it is possible to read and write modbus.
