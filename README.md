# Human-Detection-using-ESP32CAM

Complete Report : https://github.com/IshanVyas-edu/Human-Detection-using-ESP32CAM/blob/main/TensorFlow%20model/Report.pdf

Prerequisites needed - 
1) ESP32-CAM 
2) FTDI module
3) Arduino IDE 
4) TensorFlow - !pip install tensorflow

To run the following project -
1) Connect the ESP32-CAM with the FTDI module. 
2) Connect the ESP32-CAM with your machine.
3) Open esp32cam_person_detection.ino
4) Select the board as AITHINKER and select your respective port. 
5) Before uploading the code, make a small change to the code. Change the SSID and password in accordance with your WiFi network.
6) Upload the code and waiting for it to say connecting...
7) When it starts connecting..., press IO0pin and reset button simultaneously till it starts connecting. 
8) Once the code is uploaded, hit the reset button again and open your serial moniter. 
9) Serial moniter will show the ipaddress at which the webpage is online and can be opened. 
10) Open the ip address and press start detect button. 
