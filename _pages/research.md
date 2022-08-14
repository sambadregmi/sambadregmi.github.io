---
layout: archive
title: ''
permalink: /research/
author_profile: true
---

# Work
Currenlty, I am a part of the development and engineering team that is working on building the very first High-NA EUV Lithography System ([TWINSCAN EXE500](https://www.asml.com/en/news/press-releases/2022/intel-and-asml-strengthen-their-collaboration-to-drive-high-na-into-manufacturing-in-2025)).

# Ph.D Research
I worked as a graduate research assistant in the Physical Human-Robot Interaction Laboratory (pHRI Lab), which is directed by [Dr. Yun Seong Song](https://mae.mst.edu/facultyandstaff/facultysong/). The project -- "Human Arm Impedance Modulation during Overground Physical Interactions"-- was funded by National Science Foundation. As a part of my PhD, I mainly worked on two projects descried briefly below.
## Development of an Interactive Robot for Overground Physical Human-Robot Interaction ### 
### Phase I: Development of overground robot 
  * Developement of robotic arm\
  Due to the unique characteristics expected in the robot (i.e. capable of doing overground physical human-robot interection tasks), the robotic arm (manipulator) had to be designed and then built in our lab. The unique kinematic and dynamic characteristics of the robotic arm were identified and calculated. The second order non-linear dynamics of the arm was derived and hence was coded in to develop a simulator model of the robotic arm. This simulator not only helped us weighing up the effectiveness of the robotic arm based on its endpoint impedance but also will helped us in designing the effective control algorithms.
<p align="center">
  <img src="https://sambadregmi.github.io/images/physical_robot.jpg" width="200" height="200" >
</p>
<p align="center">
 Figure. The completed robotic arm.
</p>\
  * Identifying appropriate hardware and controller unit\
  Depending on the requirement of the robotic arm, it was crucial to choose appropriate actuators, sensor and controllers. Kollmorgan's actuators and AKD drivers (BLDC servo motors - to reduce friction), ATI force/torque sensors, and National Instrument's cRIO real time controller were chosen.
### Phase II: Assembly 
An autonomous mobile base (a direct drive four wheel robot) was outsourced from [SuperDroid Robots](https://www.superdroidrobots.com/shop/item.aspx/ig52-db4-4wd-all-terrain-heavy-duty-robot-platform/1648/). The body to connect the robotic arm part and the autonomous mobile base was fabricated in the workshop; the 3D CAD model was designed in order to process the fabrication using CNC machining. Ultimately, all the three parts (robotic arm, fabricated body, and the mobile base) were assembled.
<p align="center">
  <img src="https://sambadregmi.github.io/images/Robot_and_Sambad_Regmi.jpg" width="1000" height="750">
</p>
<p align="center">
 Figure. Me and the novel robot built for overground physical human-robot interaction.
</p>
### Phase III: Working with the robot
* Implementing control\
The command to control the robot arm as well was the mobile base is executed using the aforementioned NI cRIO controller (using LabVIEW software). The lower base is controlled using simple PID position control algorithm whereas the robotic arm is required to be controlled using impedance control.
* Experiment\
The integrated robot can now be used as a speed controlled trajectory tracker, as a leader of overground pHRI experiments, and is also capable of providing occasional force perturbations through the endpoint of the arm, which is the only point of communication with the human follower during the experiment. Movement data at various location/parts can be recorded during the experiment; robot motion data can be recorded using wheel encoders and vicon motion capture system whereas movement of human body parts can be recorded using vicon motion capture systems and motor encoders.\
Few months ago, we completed the experimental desing and conducted the overground physical human-robot interaction experiments. While doing so, I was involved in acquiring an IRB approval, figuring out the best data accquisition and synchronization technique, recruiting and interacting with the participants, preparing and maintaining the experiment setup, and conducting the experiment. After the experiment, we preprocessed the captured data and then analyzed it to extract meaningful information on how the human arm impedance is modulated during overground human-robot interaction. Currently, I am in porcess of putting together those outcomes to report it as a journal.
# Undergraduate Project
## Conceptualization and Fabrication of Mini-Tunnel Boring Machine
Worked together and coordinated with three other group members to come up to a concept of a portable and affordable boring machine for smaller boring projects. The concept latter was implemented as a fabricated demo model.

{% include base_path %}
[Click here to watch the video of the fabricated demo mini-tunnel boring machine.](http://sambadregmi.github.io/images/mini_tunnel_boring_machine.mp4)
