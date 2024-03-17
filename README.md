# Pepper-Docker
New Docker Image to connect and control pepper robot with pepper python SDK included.
By Carol Santhosh P

## Summary
This document is about the project using Pepper Robot ( a semi-humanoid robot), to connect and control using IoT services.

The Pepper Robot woks on python 2.7 and it can be programmed using pynaoqi-python SDK and SSH commands.  The Choregraphe Software can also be used to program it

Choregraphe Software and Python -SDK :  [Downloads Softwares | Aldebaran](https://www.aldebaran.com/en/support/nao-6/downloads-softwares)

Python SDK Installation Guide ; [Python SDK - Installation Guide — Aldebaran 2.5.11.14a documentation](http://doc.aldebaran.com/2-5/dev/python/install_guide.html)

    

## Features
- Connect to Pepper Robot
- Connect to WiFi network
- Connect to MQTT Service (Homie Conventions)
- Connect to OpenHAB
- Using Python SDK with python scripts

    

## Software
The Docker Image is built with python 2.7 and all the  basic required dependencies for pepper SDK and Projects.

[Pepper.py](http://Pepper.py) library is added to this image’s site-package, to use the Pepper’s python SDK with basic predefined functions.

### Docker Image
To Download the Docker Image


    docker pull carolsanthosh/lara-pepper:v4

To run Docker

    docker run -p 5000:5000 carolsanthosh/lara-pepper:v4
View it from https://localhost:5000/


Refer https://github.com/carolsanthosh/Pepper-Robot.git on how to use it
