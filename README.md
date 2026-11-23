# Awesome-Robotics-Frameworks-Embedded-Control

## Top Robotics Frameworks & Embedded Control Ecosystem



**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  

*Focused on Robotics Operating Systems, Embedded Real-Time Control, Physics Simulators, SLAM & Fleet Telemetry*  

**Last updated: November 2026**



This repository tracks notable **SaaS/hosted robotics cloud platforms** and **open-source GitHub projects** for **Robotics Frameworks & Embedded Control**. These tools power robot middleware (DDS/Zenoh), deterministic RTOS flight/motor controllers, physics simulation, SLAM navigation, kinematics, and cloud fleet observability across autonomous mobile robots (AMRs), manipulators, drones, and humanoid platforms.



**Examples** include ROS 2, micro-ROS, PX4 Autopilot, ArduPilot, Gazebo, Webots, Dora-rs, Copper-rs, LeRobot, Nav2, MoveIt 2, Foxglove, openrobokit/robokit, AWS RoboMaker, NVIDIA Isaac, CoppeliaSim, Viam, Formant, InOrbit, and Freedom Robotics.



**Open-source emphasis**: This list heavily expands on active open-source robotics middleware, Rust/C++ real-time control loops, microcontroller RTOS frameworks, 3D physics simulators, and open embodied AI stacks — ideal for robotics engineers, embedded firmware developers, and researchers building autonomous hardware without vendor lock-in.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[AWS RoboMaker](https://amazon.com)**  

  Managed cloud simulation and fleet deployment service by Amazon Web Services enabling large-scale parallel Gazebo/ROS testing and CI/CD regression pipelines.



- **[NVIDIA Isaac Sim & Isaac Cloud / Omniverse](https://nvidia.com)**  

  GPU-accelerated robotics simulation, synthetic data generation, and foundation-model training platform built on NVIDIA Omniverse and PhysX.



- **[Viam](https://viam.com)**  

  Cloud-connected robotics software platform combining an open-source edge runtime (`viam-server`) with managed cloud fleet monitoring, ML model deployment, and data capture.



- **[Formant](https://formant.io)**  

  Cloud robotics observability, teleoperation, and fleet management platform providing real-time sensor streaming, remote intervention, and analytics.



- **[InOrbit](https://inorbit.ai)**  

  Cloud-based RobOps and multi-vendor fleet orchestration platform offering incident response, mission dispatch, and spatial analytics for autonomous mobile robots.



- **[Freedom Robotics](https://freedomrobotics.ai)**  

  Managed cloud robotics infrastructure for real-time telemetry, low-latency WebRTC teleoperation, log replay, and fleet diagnostics.



- **[CoppeliaSim (Commercial / Edu Tiers)](https://coppeliarobotics.com)**  

  Versatile multi-physics robot simulation environment supporting distributed control architectures, Lua/Python/C++ APIs, and kinematic solvers.



- **[Foxglove Cloud](https://foxglove.dev)**  

  Cloud data management, MCAP recording storage, and collaborative visualization platform tailored for ROS 2 and custom robotics teams.



- **[Transcend Robotics / Rocos (DroneDeploy Robotics)](https://dronedeploy.com)**  

  Enterprise cloud mission control and automated inspection data platform for ground robots and aerial drones.





## Open-Source GitHub Projects



- **[RoboKit (openrobokit/robokit)](https://github.com)**  

  Open-source modular robotics toolkit and embedded control framework engineered for rapid prototyping, hardware abstraction, and reproducible robot software stacks.



- **[ROS 2 — Robot Operating System (ros2/ros2)](https://github.com)**  

  The industry-standard open-source robotics middleware suite built on DDS and Zenoh, offering real-time publish/subscribe messaging, hardware drivers, and distributed tooling.



- **[micro-ROS (micro-ROS)](https://github.com)**  

  Open-source framework bridging ROS 2 directly onto resource-constrained microcontrollers (ESP32, STM32, RP2040) running FreeRTOS, Zephyr, or NuttX.



- **[Gazebo / Gazebo Sim (gazebosim/gz-sim)](https://github.com)**  

  Flagship open-source 3D robotics simulator featuring modular physics engines (DART, Bullet), realistic sensor plugins (LiDAR, RGB-D, IMU), and tight ROS 2 integration.



- **[Webots (cyberbotics/webots)](https://github.com)**  

  Apache-2.0 open-source 3D mobile robot simulator widely used in academia and industry with built-in models for wheeled, legged, aerial, and manipulator robots.



- **[PX4 Autopilot (PX4/PX4-Autopilot)](https://github.com)**  

  BSD-licensed open-source flight control and autonomous vehicle stack running on NuttX RTOS and Linux with native MAVLink and micro-XRCE-DDS ROS 2 support.



- **[ArduPilot (ArduPilot/ardupilot)](https://github.com)**  

  Trusted, versatile GPLv3 open-source autopilot suite supporting copters, fixed-wing planes, rovers, boats, and submarines with SITL simulation.



- **[Dora-rs (dora-rs/dora)](https://github.com)**  

  High-performance, low-latency dataflow-oriented robotics framework written in Rust using zero-copy Apache Arrow shared memory for AI-heavy robotic pipelines.



- **[Copper-rs (copper-project/copper-rs)](https://github.com)**  

  Deterministic, memory-safe Rust robotics runtime engine designed for predictable real-time execution, ultra-low jitter, and high-speed logging.



- **[Nav2 — ROS 2 Navigation Stack (ros-navigation/navigation2)](https://github.com)**  

  Production-grade open-source autonomous mobile robot (AMR) navigation framework providing SLAM, costmaps, path planners, behavior trees, and recovery behaviors.



- **[MoveIt 2 (moveit/moveit2)](https://github.com)**  

  Leading open-source motion planning, inverse kinematics, collision checking, and manipulation framework for robotic arms in ROS 2.



- **[LeRobot (huggingface/lerobot)](https://github.com)**  

  Hugging Face's open-source PyTorch library for real-world robotics and imitation/reinforcement learning, providing datasets, pretrained VLA policies, and low-cost arm control.



- **[Zephyr RTOS (zephyrproject-rtos/zephyr)](https://github.com)** & **[FreeRTOS (FreeRTOS/FreeRTOS-Kernel)](https://github.com)**  

  Foundational open-source real-time operating systems powering deterministic motor control, CAN-FD/EtherCAT fieldbuses, and embedded sensor nodes.



### Additional Strong Open-Source Options



- **[Eclipse Zenoh (eclipse-zenoh/zenoh)](https://github.com)** — Ultra-low-overhead pub/sub/query protocol (`rmw_zenoh`) uniting microcontroller-to-cloud robotics communication across lossy Wi-Fi and WAN links.

- **[Foxglove Studio / Lichtblick (lichtblick-suite/lichtblick)](https://github.com)** — Open-source (MPL-2.0) visualization and debugging suite for inspecting ROS 2 topics, 3D URDF models, and MCAP logs.

- **[MuJoCo (google-deepmind/mujoco)](https://github.com)** & **[Genesis (Genesis-Embodied-AI/Genesis)](https://github.com)** — High-speed open-source physics engines engineered for contact-rich manipulation, reinforcement learning, and embodied AI simulation.

- **[SimpleFOC (simplefoc/Arduino-FOC)](https://github.com)** & **[ODrive / VESC Firmware (vedderb/bldc)](https://github.com)** — Open-source Field-Oriented Control (FOC) brushless DC motor control firmware and libraries for precision actuators.

- **[RTAB-Map (introlab/rtabmap)](https://github.com)** & **[SLAM Toolbox (SteveMacenski/slam_toolbox)](https://github.com)** — Battle-tested open-source 2D/3D LiDAR and RGB-D visual SLAM libraries for real-time mapping and localization.

- **[OpenRMF — Robotics Middleware Framework (open-rmf/rmf)](https://github.com)** — Open-source multi-fleet interoperability framework coordinating heterogeneous robots, elevators, and doors inside shared buildings.



**Frameworks for building custom systems**: Combine **Zephyr RTOS** + **micro-ROS** + **SimpleFOC** on embedded motor controllers with **ROS 2** (or **Dora-rs**) + **Nav2** + **MoveIt 2** on the companion computer, validate in **Gazebo** / **MuJoCo**, and visualize telemetry via **Lichtblick (Foxglove)**.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Physical robots, high-torque BLDC actuators, and autonomous vehicles can cause severe injury or property damage if software faults occur; always implement hardware emergency stops (E-Stop), watchdog timers, current/velocity limits, and test thoroughly in simulation (`Gazebo`, `Webots`, `SITL`) before deploying on physical hardware.

- Secure ROS 2 DDS / Zenoh discovery domains and wireless telemetry links (`MAVLink`, `WebRTC`) with SROS2 encryption and VPN tunnels (`WireGuard`/`Tailscale`) in field deployments.



---



**Made for robotics engineers, embedded firmware developers, control theorists, and open-source hardware builders.**  

Let's make robotics frameworks and embedded control deterministic, safe, and open to everyone.
