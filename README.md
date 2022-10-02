# DLW Hackathon 2022 - Smart Cane

**Topic: AI and Smart Nation**

Develop AI models or IoT solutions that solve industrial or social problems in the new stage of
society development. The Smart Nation is an initiative by the Government of Singapore to harness
from info-comm technologies, networks, and big data to create tech-enabled solutions.

**Live Demo**: https://youtu.be/jgbvyDLEyAU

## What the project does?
Allow accelerated learning for individuals who have visual impairment, through the use of radiofrequency sensors to warn and alert the user of danger.

## How does Smart Cane work?
It uses an ultrasonic sensor attached to a blind stick to measure the distance between an object and the stick. It will feedback signs of danger through a buzzer back to the user. With additional mobile software (Smart Alert), the user is able to press a button to alert surrounding people for help. The app is targeted towards user who are visually impared and mute. 

## Why should you use the Smart Cane?
It is cheap to manufacture with low material cost, easily replicable, low maintenance cost. Therefore affordable for individuals to use our Smart Cane. It is also counter-intuitive to use with very simple app interface for Smart Alert app and straightforward design for the Smart Cane. 

## How the connections work in hardware?
For Arduino:

1. Insert the L298P board into the Arduino UNO R3 board as all in one set.
2. Connect the transmit pin from L298P to receiver pin of ESP8266 Wifi Module.
3. Repeat step 2, this time to connect from receiver pin of L298P to transmit pin of ESP8266.
4. Power up the Wifi Module of 3V3 source pin from L298P to ESP8266.
5. Repeat step 4, this time to connect ground for both.
6. Lastly is to connect the reset pin for both boards of ESP8266 and L298P.
7. Finally to power up the main board of Arduino UNO by plugging in USB to Socket serial type cable from Powerbank.

For Raspberry Pi:
1. continue

## Technologies
### Backend
1. Raspbian OS
2. Python IDE
3. Arduino IDE
### Frontend
1. RemoteXY
### Language
1. C 
2. Python

## Materials needed
1. Raspberry Pi 3b+ 
2. Grove Pi
3. Arduino Uno 
4. L293D motor driver shield
5. Esp8266 wifi module
6. Jumper wires
7. Resistors
8. LED
9. Ultrasonics sensors
10. Buzzer
11. Breadboard
