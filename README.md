# INTRODUCTION
Abstract: RADAR is an object detection system which uses radio waves to determine the range, altitude and direction of objects. The radar transmits pulses of radio waves or microwaves which bounce off any object in their path. Arduino is a single-board microcontroller to make using electronics in multidisciplinary projects more accessible. This project aims at making a RADAR that is efficient, cheaper and reflects all the possible techniques that a radar consists of. 

# WORKING 
The project works on the principle of radar echo effect of the transmitting signal. Arduino control the servo motor for the direction of ultrasonic sensor and it moves from 0 degree to 180 degree. 
Ultrasonic sensor transmits the signal in all direction and if any obstacle
that is target is detected then echo pulse sense. With the help of this echo pulse arduino program find out the distance and direction angle of the target ,
On the screen of Laptop.

# SCHEMATIC
![image](https://user-images.githubusercontent.com/51716609/183061831-863e2d06-a37d-406a-ab92-2ad67b79229e.png)


Here,  Servo Motor,Ultrasonic Sensor, have their Postive and negative terminal common to Arduino’s pin having VCC=5v and Ground Trig is connected to Pin 10, Echo to Pin 11, and Servo motor to Pin12

# APPLICATIONS

- ## Defence Systems
- ## Commercial Aviaton
- ## Under sea rescue operations/wreckage detection 

