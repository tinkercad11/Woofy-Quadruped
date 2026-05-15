# Woofy-Quadruped
Woofy is a friendly quadruped robot, meant for beginners who are just starting out. Its simplicity lies in the fact that it uses only four servos, having no joints in each of the legs, making it easy to code and run. That is what makes woofy a really beginner-friendly project. 
It is designed to have only 1DOF per leg, making it very easy to create new gaits. 

## Materials 
### For robot : 
MG90(Recommended)/SG90 servo  x 4

ESP8266 NodeMcu Board  x 1

PCA9685 servo control board  x 1

1.3 inch oled display  x 1

Toggle Switch  x 1

Miscellaneous(Perfboard, headers, jumper wires)

### For Battery Pack : 
18650 cells  x 2

Suitable buck Converter  x 1

Cell holder  x 1

## Hardware 
The MG90 servos provide decent amount of torque while being within budget. The PCA9685 Expansion board is used for future scalability, making it easy to add or remove more servos. The oled displays expressions in the form of eyes. All the different expressions are already stored in the sketch, so making you own modifications is easy. The ESP8266 board allows remote control through both Wifi and bluetooth protocols. 

## Software 
The code(.ino) provided Consists of 5 different gaits(forward, backward, left, right, and hi) and 7 other positions, using a switch case logic(Again designed to make it easy to add more positions/gaits). All the gaits, and expressions are included inside the same file. The ESP8266 is made a Wifi server to which the application connects as a client. This give a reliable connection using the Wifi protocol. It also contains a blink function which gives the robot the ability to blink at a random interval of time. 

## App
The App used for controlling the robot is created using the MIT App Inventor. The code is included. The app needs an Android phone, in which you need to connect to the Wifi access point created by the ESP8266 board. Again it is designed to make sure is is easy to add more commands. 


