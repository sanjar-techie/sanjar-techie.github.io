---
layout: page
title: Projects
permalink: /projects/
description: A collection of my robotics and AI projects.
nav: true
nav_order: 2  # Adjusted to follow About (1), Publications (2)
---

<!-- _pages/projects.md -->

<div class="projects">

  <div class="project">
    <h2 class="project-title">Quadruped Robot System: Advanced Legged Locomotion</h2>
    <div class="row">
      <div class="col-md-6">
        {% include figure.liquid path="assets/img/quadruped1.jpg" alt="Quadruped Robot" class="img-fluid rounded z-depth-1" %}
      </div>
      <div class="col-md-6">
        {% include figure.liquid path="assets/img/quadruped2.jpg" alt="Quadruped Robot in Action" class="img-fluid rounded z-depth-1" %}
      </div>
    </div>
    {% include video.liquid path="https://www.youtube.com/embed/U2KB_e_6qTM" class="img-fluid rounded z-depth-1" %}
    <p><em>Technologies:</em> C++, ROS, Reinforcement Learning, Motion Planning, Control Systems</p>
    <p>Collaborated on the development of a state-of-the-art quadruped robot system, integrating advanced hardware assembly with cutting-edge software implementation. Leveraged reinforcement learning techniques to create adaptive locomotion controllers, significantly enhancing the robot's stability and versatility across diverse terrains. Implemented sophisticated motion planning algorithms and control systems, pushing the boundaries of legged robotics technology.</p>
  </div>

  <div class="project">
    <h2 class="project-title">Autonomous Mobile Robots (AMRs) for Warehouse Automation</h2>
    {% include figure.liquid path="assets/img/amr.PNG" alt="AMR in Warehouse" class="img-fluid rounded z-depth-1" %}
    {% include video.liquid path="https://www.youtube.com/embed/OQCnwZKU0rQ" class="img-fluid rounded z-depth-1" %}
    <p><em>Technologies:</em> ROS2, Nav2, C++, Apriltag Detection, Hardware Interfacing</p>
    <p>Engineered a fleet of Autonomous Mobile Robots (AMRs) for warehouse automation, focusing on robust navigation and efficient task execution. Implemented autonomous navigation systems using the Nav2 framework, ensuring optimal path planning and obstacle avoidance. Developed custom hardware interfaces and control packages, including an innovative docking system utilizing Apriltag detection, significantly enhancing the precision and reliability of robot operations in dynamic warehouse environments.</p>
  </div>

  <div class="project">
    <h2 class="project-title">Air Gesture Control: Advanced Human-Drone Interaction</h2>
    {% include figure.liquid path="assets/img/drone.PNG" alt="Gesture-controlled Drone" class="img-fluid rounded z-depth-1" %}
    {% include video.liquid path="https://www.youtube.com/embed/jC1L5EdkM9w" class="img-fluid rounded z-depth-1" %}
    <p><em>Technologies:</em> Computer Vision, Machine Learning, ROS, ORB_SLAM3, PID Control</p>
    <p>Pioneered an innovative gesture-based drone control system, merging advanced computer vision techniques with intuitive human-machine interaction. Developed a ROS-based mission planner capable of interpreting complex gestures and translating them into precise drone maneuvers. Integrated ORB_SLAM3 for robust visual navigation and implemented a sophisticated PID velocity controller, enabling smooth and accurate drone positioning. This project demonstrates the potential for revolutionizing drone control in various applications, from aerial cinematography to search and rescue operations.</p>
    <p><a href="https://github.com/sanjar-techie/AirGestureControl" target="_blank">View on GitHub</a></p>
  </div>

  <div class="project">
    <h2 class="project-title">AI in Healthcare: Advanced Dermatological Diagnostics</h2>
    <p><em>Technologies:</em> Deep Learning, TensorFlow, Computer Vision, Data Augmentation</p>
    <p>Developed an advanced skin lesion classification system using deep learning techniques, aimed at assisting dermatologists in early skin cancer detection. Implemented a custom ResNet-50 model with Convolutional Block Attention Module (CBAM), significantly improving the accuracy of lesion classification. Utilized sophisticated data augmentation techniques on the HAM10000 dataset to address class imbalance, enhancing the model's robustness and generalization capabilities. This project showcases the potential of AI in revolutionizing medical diagnostics, particularly in the field of dermatology.</p>
    <p><a href="https://github.com/sanjar-techie/lesion-classification" target="_blank">View on GitHub</a></p>
  </div>

</div>