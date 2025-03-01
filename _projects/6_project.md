---
layout: page
title: Bipedal Robot Walking
description: Optimization-Based Control
img: assets/img/biped.jpg
importance: 6
category: robotics
github: https://github.com/sanjar-techie/biped_control
---

# Bipedal Robot Walking

## Optimization-Based Control System

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/biped.jpg" title="Bipedal Robot Walking" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Bipedal robot demonstrating stable walking patterns generated through optimization-based control.
</div>

## Project Overview

I achieved stable bipedal walking by developing an optimization framework that generates joint trajectories through 6th-order polynomial parameterization. The system optimizes for center of mass (COM) stability and joint constraints via forward kinematics, resulting in smooth and balanced walking motions.

## Technical Implementation

The project involved several key technical components:

- **Trajectory Optimization**: Developed an optimization framework that generates optimal joint trajectories using 6th-order polynomial parameterization
- **COM Stability**: Implemented constraints to ensure center of mass stability throughout the walking cycle
- **Forward Kinematics**: Used forward kinematics to validate joint constraints and ensure physically realistic movements
- **Cyclic Walking**: Implemented symmetric left-right swing trajectories with smooth transitions for continuous bipedal locomotion

## Key Achievements

- Successfully achieved stable bipedal walking through sophisticated trajectory optimization
- Implemented cyclic walking by generating symmetric left-right swing trajectories
- Created smooth transitions between steps for continuous bipedal locomotion
- Developed a mathematically sound approach to bipedal locomotion based on optimization principles

## Technologies Used

- **Programming**: Python, MATLAB
- **Techniques**: Trajectory Optimization, Forward Kinematics, Robot Dynamics
- **Mathematics**: 6th-order Polynomial Parameterization, Constrained Optimization
- **Robotics**: Bipedal Locomotion, Joint Control

This project demonstrates my ability to apply advanced optimization techniques and robot dynamics principles to solve complex problems in legged locomotion.

View project code on [GitHub](https://github.com/sanjar-techie/biped_control)