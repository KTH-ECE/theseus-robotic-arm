# Theseus — An Evolving 6-DOF Robotics Platform

> A sustained, full-stack robotics project — spanning mechanical, electrical, embedded, control, and software — built on the open Arctos platform and engineered to keep evolving.

## Overview

**Theseus** is a *6-DOF robotic arm* built on the open [Arctos Robotics](https://arctosrobotics.com/) platform, running in closed-loop configuration: encoder feedback over CAN bus for precise, repeatable motion. It is not a single finished build - it is a long-running engineering platform that I extend continuously: ROS2 motion control, kinematics in MATLAB, computer vision, and eventually autonomy.

The name comes from the Ship of Theseus: a vessel whose every part is replaced over time. That paradox is the point - Theseus is meant to be rebuilt, upgraded, and re-imagined indefinitely while remaining one continuous body of work.


## What this project demonstrates

- **Mechanical** - assembled a 6-DOF arm; 3D-printed and post-processed the structural parts in-house; total 168 parts
- **Electrical** - wired and commissioned a closed-loop CAN-bus servo system with per-joint encoder feedback
- **Embedded & control** - closed-loop motor control, calibration, and bring-up debugging
- **Software** - motion control in ROS2 and forward-kinematics modeling in MATLAB/Simulink
- **Engineering** - maintained a dated [build log](docs/build-log.md) and design-decision record


## Built on Arctos - and what's mine

This project stands on the open-source [Arctos Robotics](https://arctosrobotics.com/) platform. Being clear about the boundary:
- **The Arctos platform provides** the mechanical design, base firmware, closed-loop electronics design, and an open software ecosystem (ros2_arctos, GcodeCANBus, CLMD, arctosgui, Matlab-Simulink-FK, …).
- **This repository is my work on top of it** - the physical build and bring-up, my control and kinematics experiments, my ROS2 configuration, documentation, and ongoing extensions.

> The CAD files and Arctos Studio Pro are paid Arctos products and are not redistributed here. The upstream Arctos repos are referenced, not copied - see links above.


## Tech stack & skills
CAN bus | closed-loop control | ROS2 | MATLAB / Simulink | robot kinematics | C/C++ (embedded) | Python | EasyEDA (PCB) | 3D Printing | Soldering | Git


## License

The code, documentation, and BOM in this repository are released under the **MIT License** - see [LICENSE](LICENSE.md).

The Arctos CAD files and Arctos Studio Pro are paid products, not covered by this license and not redistributed here. Upstream Arctos repositories retain their own licenses.


## Author

KIM TAEHWAN - Electrical & Computer Engineering, Sungkyunkwan University

[GitHub](https://github.com/KTH-ECE) | [LinkedIn](https://www.linkedin.com/in/taehwankim-skku) | [Email](mailto:kimtaehwan1106@gmail.com)
