---
layout: archive
title: ''
permalink: /research/
author_profile: true
---

# Work
Currenlty, I am a part of the development and engineering team that is working on building the very first High-NA EUV Lithography System ([TWINSCAN EXE500](https://www.asml.com/en/news/press-releases/2022/intel-and-asml-strengthen-their-collaboration-to-drive-high-na-into-manufacturing-in-2025)).

# Ph.D. Research
I worked as a graduate research assistant in the Physical Human-Robot Interaction Laboratory (pHRI Lab), which is directed by [Dr. Yun Seong Song](https://mae.mst.edu/facultyandstaff/facultysong/). The project - "Human Arm Impedance Modulation during Overground Physical Interactions"- was funded by National Science Foundation. As a part of my Ph.D, I mainly worked on two projects during my Ph.D., which are descried briefly below.
## Development of an Interactive Robot for Overground Physical Human-Robot Interaction
### Phase I: Development of an interactive robotic arm 
Due to the unique characteristics expected from the robot (i.e. capable of performing overground physical human-robot interection and simultaneously measure human arm impedance), we decided to desing and build the robotic manipulator in our own lab. The kinematic and dynamic characteristics required were identified. The second order non-linear dynamics of the robotic arm was derived and a simulation model was developed in Matlab. The simulation model not only helped us weighing up the effectiveness of the robotic arm based on its endpoint impedance but also will helped us design and develop an effective control algorithm. After validating the desing using simulation model, it was crucial to get actuators, sensor, controllers and accessories that would meet the design requirements. Kollmorgan's actuators and AKD drivers (BLDC servo motors - to reduce friction), ATI force/torque sensors, and National Instrument's cRIO real time controller were chosen.
<p align="center">
  <img src="https://sambadregmi.github.io/images/physical_robot.jpg" width="200" height="200" >
</p>
<p align="center">
 Figure. The completed robotic arm.
</p>
  
### Phase II: Body frame and the mobile base
An autonomous mobile base (a direct drive four wheel robot) was outsourced from [SuperDroid Robots](https://www.superdroidrobots.com/shop/item.aspx/ig52-db4-4wd-all-terrain-heavy-duty-robot-platform/1648/). The body frame that would lodge the interactive arm and the electrical accessories was designed as a 3D CAD model. It was then fabricated in the university workshop using CNC machining. All the three subsystems - robotic arm, body frame, and the mobile base - were assembled in our lab.
<p align="center">
  <img src="https://sambadregmi.github.io/images/Robot_and_Sambad_Regmi.jpg" width="1000" height="750">
</p>
<p align="center">
 Figure. Me and the novel robot built for overground physical human-robot interaction.
</p>

### Phase III: Control architecture
Designing a control framework followed next. A design decision was made to use NI cRIO as a single point of control (processor) for both the manipulator and the mobile base. I outlined a control framework using LabVIEW software wuch that the lower base was controlled through a simple PID position control algorithm whereas the robotic arm was programmed to operate through either position control or position based force control (impedance control).

## Human Arm Impedance Measurement during Overground Physical Human-Robot Interaction
The integrated robot can now be used as a speed controlled trajectory tracker, as a leader of overground pHRI experiments, and is also capable of providing occasional force perturbations through the endpoint of the arm, which is the only point of communication with the human follower during the experiment. Movement data at various location/parts can be recorded during the experiment; robot motion data can be recorded using wheel encoders and vicon motion capture system whereas movement of human body parts can be recorded using vicon motion capture systems and motor encoders.\
Few months ago, we completed the experimental desing and conducted the overground physical human-robot interaction experiments. While doing so, I was involved in acquiring an IRB approval, figuring out the best data accquisition and synchronization technique, recruiting and interacting with the participants, preparing and maintaining the experiment setup, and conducting the experiment. After the experiment, we preprocessed the captured data and then analyzed it to extract meaningful information on how the human arm impedance is modulated during overground human-robot interaction. Currently, I am in porcess of putting together those outcomes to report it as a journal.
# Undergraduate Project
## Conceptualization and Fabrication of Mini-Tunnel Boring Machine
Worked together and coordinated with three other group members to come up to a concept of a portable and affordable boring machine for smaller boring projects. The concept latter was implemented as a fabricated demo model.

{% include base_path %}
[Click here to watch the video of the fabricated demo mini-tunnel boring machine.](http://sambadregmi.github.io/images/mini_tunnel_boring_machine.mp4)
