# ctc-ecozenith-i250
For connection between CTC ecozenith i250, the old version and Homeassistant.
I haven't found all the modbus registers yet from the lists in the pdf files

![image](https://github.com/leifj79/CTC-ctc-ecozenith-i250_homeassistant/assets/114435387/2170cf4e-4d2d-4aed-a394-7b6177da7b1e)
![image](https://github.com/leifj79/CTC-ctc-ecozenith-i250_homeassistant/assets/114435387/2a2c21b4-a268-42bf-8dfc-1c49a3441f63)
![image](https://github.com/leifj79/CTC-ctc-ecozenith-i250_homeassistant/assets/114435387/edbbcbb0-4b9d-4508-a19c-8c2c4237d2d5)


RJ12 cable cut in half an connected to NodeMCU ESP32

Pinout for the RJ12 cable connected to the display of the CTC heat pump

![image-png-Jun-29-2022-09-29-07-52-AM](https://user-images.githubusercontent.com/71944008/200346393-598ecfbc-5bc0-45ca-adbf-1e089296bc18.png)

1: GND

2: 5V

3: Not used

4: RX GPIO 16

5: Flow control pin GPIO 5 

6: TX GPIO 17

![Skærmbillede 2022-11-07 152704](https://user-images.githubusercontent.com/71944008/200334618-07011627-09ad-4e66-bbed-e7b5d6aa3e4d.png)

Using Esphome it is possible to read and write modbus.
