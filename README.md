# easyDriverActuator
easyDriverActuator is Based TMC 2208 silents Stepper driver and the Atmel ATMega328P 8MH) microcontroller with RFM 69 HCW or LoRa RFM95  radio on board

![Arduino TMC2208](https://github.com/EasySensors/easyStepperActuator/blob/master/pics/TMC2208_ACTUATOR_BOTTOM.jpg?raw=true)
![Arduino TMC2208](https://github.com/EasySensors/easyStepperActuator/blob/master/pics/TMC2208_ACTUATOR_PCB_TOP.jpg?raw=true)
![Arduino TMC2208](https://github.com/EasySensors/easyStepperActuator/blob/master/pics/TMC2208_ACTUATOR_MAIN.jpg?raw=true)


**The easyPIRmultisensorsBox is a low cost wireless Arduino IDE compatible (the Atmel ATMega328P 8MHz) microcontroller with  RFM 69 CW or RFM 69 HCW or RFM 95 LoRa  radios on board and few other nice additions.** 
------------------------------------------------------------------------

Best sutable for Home Automation, IOT.  You may think of it as Arduino Pro Mini plus all the items in the picture below:

![Arduino TMC2208](https://github.com/EasySensors/easyStepperActuator/blob/master/pics/replce.jpg?raw=true)

## Specification: ##

 - MCU Atmel ATMega328P 8MHz) microcontroller
 - TMS2208 silent stepper motor driver
 - Radio- HopeRFRFM 69 HCW or RFM 95 LoRa  (915, 868 0r 433 MHz)  radio on board
 - Enclosure dimensions 95mm*40mm*20mm 
 - Powered by external power supply 3000 mA. connector 
 - Wide operating temperature range. Tested -20 +40 Celsius
 - Authentication security - Atmel ATSHA204A Crypto Authentication Chip
 - Dualoptiboot bootloader. Implements over the air (OTA) firmware update ability
 - FTDI  header for programming
 - 3 Buttons. forward back and motor trvel distance program button (middle) with LED indicator 
 

**Arduino IDE Settings**

![Arduino IDE Settings](https://github.com/EasySensors/ButtonSizeNode/blob/master/pics/IDEsettings.jpg?raw=true)


**programming FTDI adapter connection**

![enter image description here](https://github.com/EasySensors/ButtonSizeNode/blob/master/pics/FTDIvcc5-3.jpg?raw=true)


How to use it as home automation (IOT) node controller
------------------------------------------------------

easyPIRmultisensorsBox.ino is the Arduino example sketch using [MySensors](https://www.mysensors.org/) API. 


Connect the Node to FTDI USB adaptor, Select Pro Mini 8MHz board in Arduino IDE and upload the sketch.

**Done**


The board designed by  [Koresh](https://www.openhardware.io/user/143/projects/Koresh)

