---
layout: cv
permalink: /cv/
title: CV
nav: true
nav_order: 3  # Follows About (1), Publications (2), Projects (3)
cv_pdf: Sanjar_Atamuradov_CV.pdf  # Place your PDF in assets/pdf/ or use an external URL
description: >
  Sanjar Atamuradov | 
  <a href="mailto:satamuradov3@gatech.edu"><i class="fas fa-envelope"></i> satamuradov3@gatech.edu</a> | 
  <a href="https://github.com/sanjar-techie"><i class="fab fa-github"></i> sanjar-techie</a> | 
  <a href="https://linkedin.com/in/sanjar-techie"><i class="fab fa-linkedin"></i> sanjar-techie</a> | 
  <a href="https://sanjar-techie.github.io/portfolio"><i class="fas fa-globe"></i> sanjar-techie.github.io/portfolio</a>
toc:
  sidebar: left
---

## Education

- **KAIST, South Korea**  
  *B.S. in Computer Science*  
  *August 2020 – Present*  
  Major GPA: 3.5/4.0

- **Georgia Institute of Technology, Atlanta, GA**  
  *Visiting Researcher / Student, Computer Science*  
  *August 2024 – Present*  
  Major GPA: 3.7/4.0

## Research/Work Experience

### LIDAR Lab, Georgia Institute of Technology, US  
*Research Assistant*  
*January 2025 – Present*
- (Paper in submission) Developed a diffusion-based motion planning framework that generates keypoint trajectories (root, hands, feet) for humanoid loco-manipulation, using action chunking techniques inspired by VLA models to enable complex long-horizon tasks.
- Implemented a privileged-information RL controller that leverages proprioceptive data and target keypoints to generate optimal joint positions to be passed to a PD controller.

### Raion Robotics (KAIST RaiLab spin-off), South Korea  
*AI Robotics Engineer Intern*  
*March 2024 – August 2024*
- Developed robotic operator interface with real-time 3D visualization and camera systems, integrating physics simulation using Raylib and ImGui in C++.
- Researched RL-based quadrupedal robot locomotion using privileged learning and temporal convolutional networks, focusing on zero-shot generalization to unseen terrain conditions.

### Digitrack Inc., Daegu, South Korea  
*Robotics Software Engineering Intern*  
*May 2023 – August 2023*
- Built an Autonomous Mobile Robot (AMR) from scratch for warehouse automation, integrating hardware (motors, sensors) and software (ROS2, Nav2) to achieve autonomous navigation.
- Wrote a hardware interface for `ros2_control`, managing feedback reading and wheel command writing to motor controller over RS485 serial communication.
- Developed vision-based precision docking system using AprilTag detection, achieving 0.5cm positioning accuracy for automated charging.

## Projects

### Mobile Manipulation using LeRobot Framework  
[<i class="fab fa-github"></i> View on GitHub](https://github.com/sanjar-techie/lerobot)
- Implemented LeRobot framework to train a navigation policy for a mobile robot, utilizing imitation learning with teleoperated demonstrations for efficient data collection.
- Optimized UART for low-latency communication and reliable device management with udev rules.

### Bipedal Robot Walking Control  
[<i class="fab fa-github"></i> View on GitHub](https://github.com/sanjar-techie/biped_control)
- Achieved stable bipedal walking by developing an optimization framework that generates joint trajectories through 6th-order polynomial parameterization, optimizing for COM stability and joint constraints via forward kinematics.
- Implemented cyclic walking by generating symmetric left-right swing trajectories and joining multiple steps with smooth transitions, achieving continuous bipedal locomotion.

### Autonomous Gesture-controlled Drone  
[<i class="fab fa-github"></i> View on GitHub](https://github.com/sanjar-techie/AirGestureControl)
- Developed a state machine-based mission planner for various aerial maneuvers, such as human approach and photo capture based on detected pose.
- Implemented Visual SLAM for autonomous navigation and developed PD control system for stable drone flight control.

## Technical Proficiencies

- **Languages & Tools:** C/C++, Python, Java, MATLAB, Git, Docker  
- **Robotics:** ROS2, SLAM, Navigation, Control Systems, Robot Kinematics/Dynamics  
- **AI/ML:** PyTorch, TensorFlow, Computer Vision, Reinforcement Learning, Path Planning  
- **Software:** Data Structures, Algorithms, MySQL/Databases, System Design, OpenCV  