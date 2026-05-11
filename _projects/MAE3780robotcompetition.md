---
layout: project
title: "MAE3780 Robot Compeition"
description: Homework
image: /assets/images/RobotCAD.png
technologies: [Autodesk Fusion, Laser Cutting]

---

For MAE3780, we had to design a robot that can gather as many cubes as possible. My main task was designing the chassis of the robot. 

The robot is shaped as a 7.5 by 7.5 inch rectangular prism. The cube intake runs along one entire side of the rectangular prism. The wheels consisted of the default wheels with rubber bands taped over in order to provide more traction. The motors for the wheels were placed in the middle of the robot, while a caster ball was placed in the rear opposite to the intake. To maintain weight balance and prevent the robot from tipping forward, the electronics, such as the breadboard, Arduino, and battery pack, were mounted between the main wheels and the caster wheel. The intake was made the entire length of the robot, as shown in the picture below, in order to gather as many cubes as possible on a single pass. There is a triangular barrier in front of the wheels for the blocks to funnel past the wheels and into the back of the robot.


<img src="{{ site.baseurl }}/assets/images/RobotCAD.png" alt="Robot CAD" width="100%">

The initial design emphasized placing the wheels close together to reduce the turning radius, theoretically allowing it to turn more quickly than other robots. However, because the wheels were so close, there was a need to add anti-tip tips on the side of the robot to prevent the robot from tipping. However, because the wheels were so close together initially, the robot faced significant difficulty turning. As a result, the distance between the wheels was forced to increase to the distance shown.

The chassis of the robot was initially meant to be 3D printed, but due to budget constraints, the manufacturing method was changed to laser cutting. This involved having to divide up the CAD of the chassis into multiple pieces, along with drawing in geometry for the nuts and bolts for assembly, as shown below.

<img src="{{ site.baseurl }}/assets/images/RobotCutCAD.png" alt="Robot CAD" width="100%">

