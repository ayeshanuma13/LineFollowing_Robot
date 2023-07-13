# LineFollowing_Robot
This project demonstrates the utilization of sensors and Arduino Uno microcontroller board to develop a Line Follower Robot that adeptly follows a black line while incorporating obstacle avoidance functionality.

The Line Following Robot is an autonomous robot that detects a path and
according to the path drawn, it follows the path with the help of an IR sensor
attached to the robot. The path is a distinguishable black line drawn over a white
surface thus avoiding any detection error. The robot also consists of an obstacle
sensor that detects any obstacle in its path thus avoiding any unnecessary
accidents.

Line follower robot is designed and programmed in such a way that
it does its job perfectly without any error and detects it’s given path. It operates in
such a way that it detects and reads the path and transmits the signal to Arduino
UNO. The microcontroller decides to make any changes (if needed) in the
directions or speeds of the robot according to the inputs received. Thus, it sends
the control signal to the speed and directions of the line follower robot. This way
the line follower robot operates without any error. To make a line follower robot
with object detection ability it is attached with an ultrasonic sensor, which is a
device that can measure the distance between an object and robot by using sound
waves. It calculates the distance between itself and the object obstructing it by
sending a sound wave of a specific frequency and detecting the bounced sound
wave at the receiver.

It is important to understand that some objects might not be detected by
ultrasonic sensors. This can be applied for military purposes, delivery services,
transportation systems, blind assisting applications
