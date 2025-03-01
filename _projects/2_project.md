---
layout: page
title: Autonomous Mobile Robots
description: Warehouse Automation Systems
img: assets/img/amr.PNG
importance: 2
category: automation
---

# Autonomous Mobile Robots (AMRs)

## Warehouse Automation Systems

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/amr.PNG" title="AMR in Warehouse Environment" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Custom-built Autonomous Mobile Robot (AMR) designed for warehouse automation applications.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="https://www.youtube.com/embed/OQCnwZKU0rQ" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Video demonstration of AMRs operating in warehouse environments, showcasing autonomous navigation and precision docking.
</div>

## Project Overview

During my internship at Digitrack Inc., I engineered a fleet of Autonomous Mobile Robots (AMRs) for warehouse automation, focusing on robust navigation and efficient task execution. This project involved building the AMR system from scratch, integrating both hardware components and software frameworks to create a fully functioning autonomous solution.

## Technical Implementation

The development process included several key technical components:

- **Hardware Integration**: Assembled the physical robot platform, integrating motors, sensors, and other hardware components
- **ROS2 Implementation**: Developed the software architecture using ROS2 and Nav2 frameworks
- **Hardware Interface**: Wrote a custom hardware interface for ros2_control, managing feedback reading and wheel command writing to motor controller over RS485 serial communication
- **Autonomous Navigation**: Implemented path planning and obstacle avoidance algorithms for efficient warehouse navigation
- **Vision-Based Docking**: Developed a precision docking system using AprilTag detection, achieving 0.5cm positioning accuracy for automated charging

## Key Achievements

- Successfully built a complete AMR system from the ground up, integrating hardware and software components
- Achieved reliable autonomous navigation in dynamic warehouse environments
- Implemented a precision docking system with 0.5cm accuracy for automated charging
- Developed robust communication protocols between robot components using RS485 serial communication

## Technologies Used

- **Programming**: C++, Python
- **Frameworks**: ROS2, Nav2
- **Computer Vision**: AprilTag detection
- **Hardware Communication**: RS485 serial protocol
- **Control Systems**: Custom hardware interface for ros2_control

This project demonstrates my ability to develop complex robotic systems that combine hardware integration with sophisticated software implementations for practical industrial applications.