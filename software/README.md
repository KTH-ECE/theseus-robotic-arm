# Software

This folder will hold my own code and configuration for Theseus (in progress). It builds on the open-source [Arctos Robotics](https://arctosrobotics.com/) ecosystem - the upstream repositories below are referenced, not copied.

Theseus runs the closed-loop (CAN bus) configuration.

## Arctos ecosystem (built on)

### Closed-loop control chain

- [CLMD-Closed-Loop-Motor-Driver](https://github.com/Arctos-Robotics/CLMD-Closed-Loop-Motor-Driver) - closed-loop servo driver (encoder motors): control & communication
- [GcodeCANBus](https://github.com/Arctos-Robotics/GcodeCANBus) - converts and streams G-code commands to the CAN bus
- [arctosgui](https://github.com/Arctos-Robotics/arctosgui) - GUI control over CAN bus with ROS1 MoveIt
- [Arctos-Studio-plugins](https://github.com/Arctos-Robotics/Arctos-Studio-plugins) - plugins extending Arctos Studio Pro

### Tooling I plan to use

- [ros2_arctos](https://github.com/Arctos-Robotics/ros2_arctoss) - official ROS2 package to control the arm
- [Matlab-Simulink-FK](https://github.com/Arctos-Robotics/Matlab-Simulink-FK) - forward kinematics in MATLAB / Simulink (Simscape Multibody)
- [Computer-vision](https://github.com/Arctos-Robotics/Computer-vision) - camera-based object recognition + arm integration (planned)
- [RoboDK](https://github.com/Arctos-Robotics/RoboDK) - control / simulate the arm in the RoboDK simulator


## My code

Populates as I build out each part:

|  Folder |                  Contents                 |
|:-------:|:-----------------------------------------:|
| matlab/ |      my MATLAB / Simulink experiments     |
|  ros2/  |     my ROS2 work, built on ros2_arctos    |
| vision/ | camera / perception experiments (planned) |