A gesture controlled robot is controlled by using hand in place of any other method like buttons or joystick. Here one only needs to move hand to control the robot. 
A transmitting device is used in your hand which contains Bluetooth and accelero-meter. This will transmit command to robot so that it can do the required task like moving forward, reverse, turning left, turning right and stop. 
All these tasks will be performed by using hand gesture.

Accelerometer is a 3 axis acceleration measurement device with +-3g range. This device is made by using polysilicon surface sensor and signal conditioning circuit to measure acceleration.
The output of this device is Analog in nature and proportional to the acceleration. 
This device measures the static acceleration of gravity when we tilt it. And gives an result in form of motion or vibration.


We used phone to transmit command to the robot.Phone has in-built accelero-meter and bluetooth.Phone was paired with bluetooth sensor in the robot.
An App was created to transmit the accelero-meter values to the bot.

**APP LINK : https://drive.google.com/file/d/1yRdzylaV7zZTHrXqdVAr4lcwMBNz_xoC/view?usp=sharing**

###### Arduino-Bluetooth Interfacing

HC 05/06 works on serial communication. The Android app is designed to send serial data to the Arduino Bluetooth module when a button is pressed on the app. 
The Arduino Bluetooth module in the robot at the other end receives the data and sends it to the Arduino through the TX pin of the Bluetooth module (connected to RX pin of Arduino). 
The code uploaded to the Arduino checks the received data ,compares it  and does the required task. 

![picture](/home/chocka/repos/gesture-controlled-robot/Arduino Bluetooth Hardware.png)


