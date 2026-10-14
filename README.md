# Awesome-Teleoperation

## Top Teleoperation Tools Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Remote Robot Control, Low-Latency Streaming & Fleet Supervision*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Teleoperation**. These tools enable remote operation of robots, vehicles, and heavy machinery — providing low-latency video streaming, reliable command channels, and safety mechanisms for operators to intervene when autonomy falls short.



**Examples** include Formant, Freedom Robotics, InOrbit, Phantom Auto, DriveU.auto, Ottopia, Teleo, Fernride, Vimaan, and Guident (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom teleoperation stacks, and transparent robot control — ideal for robotics researchers, fleet operators, and developers building remote operation platforms.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Formant](https://formant.io/)**  

  Cloud platform for robot fleet operations with teleoperation capabilities, live video streaming, and remote diagnostics. Provides operator interfaces for remote assistance and intervention.



- **[Freedom Robotics](https://www.freedomrobotics.ai/)**  

  Robot management and teleoperation platform with remote control, video streaming, and fleet monitoring for autonomous systems.



- **[InOrbit](https://www.inorbit.ai/)**  

  Robot operations (RobOps) platform with teleoperation tools, real-time monitoring, and fleet coordination for mobile robots.



- **[Phantom Auto](https://phantomauto.com/)**  

  Remote operation platform for autonomous vehicles and industrial equipment with low-latency video and safety-certified control channels.



- **[DriveU.auto](https://www.driveu.auto/)**  

  Connectivity platform for teleoperation of autonomous vehicles with adaptive video compression and network resilience.



- **[Ottopia](https://ottopia.tech/)**  

  Teleoperation software platform for autonomous vehicles and robots with safety-critical remote control architecture.



- **[Teleo](https://www.teleo.ai/)**  

  Teleoperation platform for heavy construction equipment, enabling remote operation of bulldozers, excavators, and loaders.



- **[Fernride](https://fernride.com/)**  

  Teleoperation platform for autonomous logistics vehicles with remote driving and fleet management capabilities.



- **[Vimaan](https://vimaan.ai/)**  

  Warehouse inventory intelligence platform with drone teleoperation and remote monitoring for supply chain operations.



- **[Guident](https://guident.com/)**  

  Remote monitoring and teleoperation platform for autonomous vehicles with safety and assistance services.



## Open-Source GitHub Projects



- **[TUM Teleoperation](https://github.com/TUMFTM/teleoperated_driving)**  

  The most complete open-source teleoperation software stack for automated vehicles, published at IEEE IV 2025 . Features **Remote Driving** (direct steering wheel/pedals) and **Remote Assistance** (high-level trajectory guidance) modes. Standardized interfaces for integration with Autoware and simulation platforms. Modular architecture with flexible HMI design. Supports real-world vehicle testing and user studies. ROS 2 implementation available .



- **[TELECARLA](https://github.com/hofbi/telecarla)**  

  Open-source extension of the CARLA simulator for teleoperated driving research using off-the-shelf components . 49+ GitHub stars, actively maintained. Provides realistic simulation environment for testing teleoperation concepts before real-world deployment.



- **[Phantom Bridge Client](https://github.com/PhantomCybernetics/phntm_bridge_client)**  

  Fast WebRTC + Socket.io ROS 2 bridge for real-time data and video streaming, teleoperation, and remote robot monitoring . Features ROS2 node/topic/service discovery, H.264 video streaming (software/CUDA/VAAPI encoding), Docker container control, reliable service/action calls, and P2P or TURN server connectivity. Achieves **~5-10ms RTT over local Wi-Fi**, ~50ms via TURN server, ~60ms on 4G LTE .



- **[OpenTera](https://github.com/introlab/opentera)**  

  Open TeleRehabilitation Server and Micro-Services with WebRTC signaling server for robot teleoperation . Includes `opentera-webrtc-ros` ROS package and Vue3.js frontend for building custom teleoperation interfaces.



- **[helyOS Control Tower](https://github.com/FraunhoferIVI/helyOS)**  

  Fraunhofer IVI's open-source control tower framework for mobile machines . Event-driven architecture with microservices for mission orchestration, path planning, and collision avoidance. Dockerized deployment with vehicle simulators, JavaScript UI SDK, and ROS compatibility. Used in logistics, agriculture, and heavy machinery applications.



- **[xr-robot-teleop-server](https://pypi.org/project/xr-robot-teleop-server/)**  

  High-performance Python server for streaming 360° panoramic video and full-body tracking data to XR headsets (Quest 3, Vision Pro) for immersive teleoperation . Built on aiortc and FastAPI for WebRTC communication. Features 360° video reprojection based on head orientation, full-body/hand skeleton processing, hardware-accelerated decoding, and coordinate system utilities.



- **[BEAVR](https://github.com/ARCLab-MIT/BEAVR-Bot)**  

  Bimanual, multi-embodiment, accessible VR teleoperation system from MIT . Hand tracking via Meta Quest 3S at 90Hz with 24 keypoints per hand (OpenXR standard). Modular architecture with IK solver, anti-collision, and temporal smoothing. Integrates with LeRobot framework for data collection and policy training.



- **[unitreerobotics/xr_teleoperate](https://github.com/unitreerobotics/xr_teleoperate)**  

  Teleoperation of Unitree humanoid robots using XR devices . 1,287+ GitHub stars, actively maintained. Part of a broader ecosystem including Open-TeleVision, OmniH2O, and TWIST for humanoid whole-body teleoperation.



- **[lerobot_franka_teleop](https://github.com/Shenzhaolong1330/lerobot_franka_teleop)**  

  Teleoperation framework for Franka Research 3 with joint-level master-slave isomorphic mapping and end-effector pose teleoperation, built on LeRobot . 48+ GitHub stars.



- **[SpesRobotics/teleop](https://github.com/SpesRobotics/teleop)**  

  Turns your phone or VR headset into a robot arm teleoperation device by leveraging WebXR . 282+ GitHub stars, actively updated. Hardware-agnostic approach using commodity devices.



- **[Mobile ALOHA](https://github.com/MarkFzp/mobile-aloha)**  

  Bimanual mobile manipulation framework for learning whole-body robot control with integrated imitation learning pipeline . Features robotic teleoperation interface mapping human movements to mobile robot with dual arms, whole-body motion dataset tools, and behavior model training.



- **[Fail-safe Remote Teleoperation for ROS 2](https://github.com/topics/teleoperation?l=c%2B%2B)**  

  C++ ROS 2 package for remote teleoperation over MQTT with deadman switch, heartbeat monitoring, and automatic stop on failure . Supports joystick or simulated ESP32 input across any network.



- **[3D Mouse HID](https://github.com/hcrlab/3dmouse-hid)**  

  Filtering and visualization for 3D mouse robot control . Enables precise 6-DOF input for teleoperation.



### Additional Strong Open-Source Options



- **[CoRL 2024 Open-TeleVision](https://github.com/OpenTeleVision/TeleVision)** — Teleoperation with immersive active visual feedback. 1,193+ GitHub stars .

- **HumanPlus** — Humanoid shadowing and imitation from humans. 821+ GitHub stars .

- **TWIST** — Teleoperated whole-body imitation system. 688+ GitHub stars .

- **AMO (OpenTeleVision)** — Adaptive motion optimization for hyper-dexterous humanoid whole-body control. 321+ GitHub stars .

- **MINI PUPPER Teleop** — MiniPupper robot teleoperation via ROS and WebRTC .

- **Pepper Telepresence Toolkit** — SoftBank Robotics toolkit for Pepper QiSDK telepresence and teleoperation applications .

- **PAL Robotics TIAGo** — TIAGo robot packages with teleoperation support .

- **Robotic-Bot (AkhilRai28)** — ROS-based teleoperated and autonomous robot with PID control .



**Frameworks for building custom systems**: Combine **TUM Teleoperation** for vehicle teleoperation with Autoware integration, **Phantom Bridge Client** for low-latency WebRTC streaming over ROS 2, **xr-robot-teleop-server** for XR headset-based immersive control, **helyOS** for fleet-level mission orchestration, and **BEAVR** for VR-based manipulation to build a complete self-hosted teleoperation stack.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Teleoperation tools must comply with safety regulations, network security standards, and applicable laws for remote operation of vehicles and machinery. Safety-critical teleoperation requires rigorous validation before deployment.

- Self-hosted open-source solutions require proper security hardening, network planning, and safety mechanism verification.



---



**Made for robotics engineers, fleet operators, teleoperation developers, and researchers building remote robot control platforms.**  

Let's make teleoperation more open, low-latency, and safety-conscious.
