# Rishabh Verma

[vermarishabh2000@gmail.com](mailto:vermarishabh2000@gmail.com) | (929) 689-8525 | [Portfolio Website](https://river2000.github.io/) | [LinkedIn](https://linkedin.com/in/river2000/) | [GitHub](https://github.com/RiVer2000)

## Education

**New York University** — Brooklyn, NY  
**Master of Science - Mechatronics and Robotics**, GPA: 3.8/4.0  
Sep 2023 - May 2025

**Visvesvaraya National Institute of Technology** — Nagpur, India  
**Bachelor of Technology - Mechanical Engineering**, GPA: 8.14/10.0  
July 2019 - May 2023

## Experience

### BotCrew

**Robotics Engineer (Autonomy & Perception)**  
May 2025 - Jul 2026

- Developed NMPC Controller for Reeds-Shepp trajectories with gradient-based smoothing, deployed on a Nvidia Jetson Orin.
- Built bracket detection using YOLO26 + TensorRT, generating waypoints for autonomous robot alignment during solar module placement.
- Led development of a FastDDS-based middleware pipeline for real-time data exchange across distributed robot modules.

**Robotics Engineering Intern (State Estimation & Mapping)**  
Feb 2025 - May 2025

- Designed a ROS-agnostic mapping engine, scaling to 5,000+ acre maps enabling deployment on the company’s largest test field sites, showcased in live investor demo.
- Fused ORB-SLAM3 and OpenVINS odometry via an Extended Kalman Filter, improving navigation robustness in dynamic environments.

### Agile Robotics and Perception Laboratory

**Graduate Research Assistant (Collision Avoidance)**  
Sep 2023 - Jan 2025

- Co-authored research on NMPC-based obstacle avoidance using adaptive control barrier functions derived from real-time risk estimates at ICRA 2025.
- Built a monocular depth-completion pipeline using DepthAnythingV2, calibrating relative depth against sparse RGB-D data to generate dense time-to-collision maps.
- Optimized quadrotor platform design via firmware improvements, achieved 26% increase in flight time.
- Built a multi-source odometry pipeline (OpenVINS + PX4 IMU/barometer) for robust navigation in GPS-denied environments.

### Defence Research Development Organisation (DRDO)

**Undergraduate Research Intern (Autonomy)**  
May 2022 - Dec 2022

- Built a navigation pipeline for urban environments in CARLA, validated across various weather conditions and multiple maps.
- Implemented PID control and A* path planning for precise vehicle navigation.
- Deployed YOLOv5 pedestrian detection, achieving collision-free navigation across crowded intersections.

## Publications

- A. Saviolo, N. Picello, R. Verma, J. Mao, & G. Loianno.  
  *“Reactive Collision Avoidance for Safe Agile Navigation”*, IEEE International Conference on Robotics and Automation (ICRA), 2025.

- R. Verma, J. Phillip, M. Kotambkar.  
  *“From Concept to Reality: An In-Depth Review of Autonomous Driving Strategies and Their Implementation”*, International Conference on Mechanical Design and Manufacturing, 2023.

## Key Projects

### Monocular Depth Estimation
[GitHub](https://github.com/RiVer2000/monocular_depth_estimation)

- Implementation of DenseDepth with a ResNet34 encoder swapped in place of the original backbone, paired with a bilinear-upsampled decoder and skip connections.
- Achieved inference at 30 FPS on a Jetson Orin NX with MIPI camera input, validating real-world deployability.

### Semi-Autonomous Urban Litter-Cleaning Robot
[GitHub](https://github.com/RiVer2000/litter-bot)

- Built a mobile robot combining Raspberry Pi + Arduino to autonomously detect and collect litter using an ultrasonic-triggered MobileNetV2 detection pipeline.
- Coordinated sensor data, image capture, and robotic arm control over UART for closed-loop trash collection.

### Robust Quadcopter Control in Windfield
[GitHub](https://github.com/IvLabs/robust_control_in_windfield)

- Designed and assembled a quadrotor from scratch, with off-the-shelf motors/ESCs/props and fabricating custom 3D-printed mounts.
- Designed a control architecture to reduce drift, benchmarking PID, LQR, MPC, and Geometric controllers in simulation at 1-5 m/s.

## Skills

**Languages and Tools:**  
C, C++, Python, Git, Docker, MATLAB, Simulink, Arduino IDE, SolidWorks

**Robotics:**  
ROS2, Gazebo, PX4, CARLA, PyTorch, TensorRT, CycloneDDS, FastDDS, Optimal Control, Model-Based Control, Visual Odometry, Camera Calibration, State Estimation, Lucas-Kanade Tracking