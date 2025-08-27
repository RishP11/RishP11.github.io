---
layout: page
title: Park Assist
description: An Ultrasonic-Sensor-Based Automotive Parking Aid
img: assets/img/parking_sensor.svg
importance: 2
category: work
---
[💻 Code](https://github.com/RishP11/Group02.git) | [📄 Documentation](https://github.com/RishP11/Group02/blob/master/README.md)


This was a final project of the course - EE 615 Embedded Systems Design and Lab - I took during my fourth year. Initially, we (me and my team-mate) had only planned to use two sensors (imitating the front and rear of a car) and using different color LEDs as a visual aid to get a sense of distance. In the end (a day before the presentation 😅), I was able to write a driver for the 0.96in monochrome OLED display. Hence, we added a feature that output the distance to the obstruction in cm(s).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/parking_sensor.svg" title="system_diag" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The hardware block diagram implementation of the System.
</div>

This project uses ultrasonic sensors and the TI TM4C123GH6PM microcontroller to measure distance and detect obstacles for a parking assist system. The system includes an OLED display for distance readouts and onboard LED signaling. The system can switch between front and rear sensors based on the gear selected, simulating a car's parking system.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/parking_sensor_software.svg" title="soft_system_diag" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The software flowchart involved. 
</div>