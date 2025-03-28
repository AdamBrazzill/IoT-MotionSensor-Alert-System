# IoT-MotionSensor-Alert-System
A smart Motion and light detection System using a Raspberry PI.


## Project Overview
This project is a Smart Motion & Light detection System built using a raspberry PI and Grove Sensors. It will also aim to detect any motion in the room and then trigger alerts based on light conditions. All events are logged and can be seen or sent to a cloud IoT platform.


## Project Idea

This projet will build a Raspberry PI based IoT System:
It will
- Detect motion using the Mini PIR Sensor
- Measure light using the Grove Light sensor
- Triggers a buzzer and LED alerts
- Optionally, can add a relay to power an external device (light etc)
- Logs all events to a local file
- Sends motion data to the cloud. (Azure)


## Hardware 

Raspberry PI
Grove MINI Pir Sensor
Grove Light Sensor
Grove Buzzer
Grove LED Red button
Grove Relay
Grove base hat


# IoT Architecture

### Sensor Layer
Grove PIR Motion Sensor : Detects moption
Grove Light Sensor : Measures light level
Both Sensors are connected to the PI.

### Processing Mode
Raspberry PI running Python handles:
Reading sensor data
Making decisions
Logging

### Gateway Layer
The PI will act as gateway, capable of:
Sending alerts
Communicating with Azure

### Application Layer
Data:
Logged locally
Used to triigger alerts


Adam Brazzill 
IoT Standards and Protocols
20103467
21/03/2025
