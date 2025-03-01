---
layout: page
title: Gesture-based Drone Control
description: Advanced Human-Drone Interaction
img: assets/img/drone.PNG
importance: 3
category: work
github: https://github.com/sanjar-techie/AirGestureControl
---

# Air Gesture Control

## Advanced Human-Drone Interaction

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/drone.PNG" title="Gesture-controlled Drone System" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Drone system with innovative gesture-based control interface for intuitive human-machine interaction.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="https://www.youtube.com/embed/jC1L5EdkM9w" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Demonstration of the drone responding to human gestures for navigation and task execution.
</div>

## Project Overview

I pioneered an innovative gesture-based drone control system, merging advanced computer vision techniques with intuitive human-machine interaction. This project explores new paradigms for controlling unmanned aerial vehicles through natural human gestures, making drone technology more accessible and user-friendly.

## Technical Implementation

The project involved several key technical components:

- **State Machine Mission Planner**: Developed a ROS-based mission planner capable of interpreting complex gestures and translating them into precise drone maneuvers
- **Visual SLAM**: Integrated ORB_SLAM3 for robust visual navigation in GPS-denied environments
- **Computer Vision**: Implemented gesture recognition algorithms to detect and interpret human movements
- **Control System**: Developed a sophisticated PD velocity controller for smooth and accurate drone positioning
- **Aerial Maneuvers**: Programmed various predefined aerial maneuvers, including human approach and photo capture based on detected poses

## Key Achievements

- Successfully implemented a gesture recognition system that accurately interprets human movements
- Developed a robust mission planning system that translates gestures into specific drone behaviors
- Integrated Visual SLAM for autonomous navigation in various environments
- Created an intuitive interface that allows non-technical users to control drones through natural movements

## Technologies Used

- **Programming**: Python, C++
- **Frameworks**: ROS, OpenCV
- **Computer Vision**: Pose detection, Visual SLAM (ORB_SLAM3)
- **Control Systems**: PD control, drone flight dynamics
- **State Machines**: Mission planning and behavior coordination

This project demonstrates the potential for revolutionizing drone control in various applications, from aerial cinematography to search and rescue operations, by making drone interaction more intuitive and accessible.

View project code on [GitHub](https://github.com/sanjar-techie/AirGestureControl)