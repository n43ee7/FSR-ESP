# FSR for ESP8266
_____________________________________________________________________________
DIY Smart Insole to Check Your Pressure Distribution using ESP8266 and Thinger.io and visualise data by using Adafruit RGB led stips. Furthermore it is an IoT project that can be further implemented for many other projects.
____________________________________________________________________________

## Libraries Used
____________________________________________________________________________
ESP8266WiFi \
__ThingerWifi__ \
Adafruit_Sensor \
Adafruit_ADXL345_U \
__ThingerESP8266__
____________________________________________________________________________
## Setup and Debugging options
Change lines 14-18 according to your AP (Wifi) and make sure pins on the __ESP__ are the following on the board. \
__FSR1 on D6 (GPIO12)   
FSR2 on D7 (GPIO13) \
FSR3 on D8 (GPIO15)__  
 
 Serial Interface is set to be on __115200__ so connect there when debugging 
