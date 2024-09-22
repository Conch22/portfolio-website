---
title: "OSL Bidirectional Neuroprosthesis"
date: 2024-07-01
draft: false
github_link: https://github.com/Conch22/ReLLiNC_OSL
# author: "Gurusabarish"
tags:
  - Python
  - MATLAB
  - SOLIDWORKS
image: /img/OSL/IMG_8638.jpg
description: "Full OSL assembly"
toc: 
# layout: "gallery"
---
# Introduction
Individuals with lower-limb loss often report diminished balance confidence and an increased risk of falls compared to their able-bodied peers, primarily due to absence of sensory feedback from their missing limb and the lack of intuitive control over their prosthesis. A **bidirectional neuroprosthesis** would restore sensory feedback from foot-floor interactions and capture user intent for intuitive motor control.I aimed to mitigate these challenges by developing a bidirectional neuroprosthesis designed to interface with the PNS in the residual limb.

{{< figure src="/img/OSL/leg.png" style="width: 20%">}}

I utilized the **Open Source Leg v2.0**, developed by the University of Michigan, as the prosthesis platform in this project. This self-contained two degree-of-freedom powered prosthesis offers a 120 and 60 degree range-of-motion in the knee and ankle joints, respectively, and features a belt drive transmission ratio of 45.0 across both joints. The OSL is equipped with two inertial measurement units (IMUs), a six-DOF loadcell, dual joint encoders, and actuators from Dephy Inc. The testing and data acquisition setup I employed included a Raspberry Pi 4 as a single-board microcomputer which communicated with the sensors and actuators via a digital bus.

# Bench Testing
{{< figure src="/img/OSL/IMG_8521.jpg">}}

 Bench testing demonstrated successful engagement with the low-level controller system by adjusting the stiffness and damping coefficients between 400-600 and 200-300, respectively, at each joint. Furthermore, I were able to stream joint angle from the integrated sensors at a 100 fps framerate and thereby verify the reliability of the connection with the Raspberry Pi. With the successful assembly, internal sensor access, and validation of the low-level control system, I have established the foundation for future development of mid and high-level control systems and integrating the OSL into a neurally integrated bidirectional lower limb prosthesis. Future work will focus on clinical testing of the OSL’s low-level control system with two participants. 

# Next Steps
This past summer, I began working on developing the interface between the OSL and the nervous system, specifically through the implementation of a myoelectric controller that has been previously created for and currently being approved by the FDA. The work has now been passed on to other graduate students.