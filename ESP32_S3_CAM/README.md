# Firmwares pour ESP32-S3-Cam Freenove

1) esp32s3_camera_st7789_n8r8_1.20.bin
   
   https://github.com/Freenove/Freenove_ESP32_S3_WROOM_Board/tree/main/Python/Python_Codes/05.1_Camera_WebServer

Pour le Camera_WebServer, voir le tuto Freenove "Python_Tutorial.pdf".

Attention :
 - les pins 35, 36, 37 sont indisponibles a cause de la PSRAM (?) (marquées * sur la board)
 - quand on utilise le module avec une SDcard, les pins 38, 39, 40 sont indisponibles (marquées ~ sur la board)
 - quand on utilise la caméra, les pins 4 à 18 (sauf 14) sont indisponibles (soulignées sur la board)
 - la pin 48 est utilisées par la neopixel
 - release micropython ancienne : 1.20 (2023-11-25)

Le firmware contient le driver pour le st7789 (non testé)

2) firmware.bin
   
   voir https://github.com/cnadler86/micropython-camera-API

 Basé sur une release micropython récente : 1.27 (2026-01)

