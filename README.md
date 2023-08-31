# AVRS
### AI Vision based Autonomous system aiming for Industrial Inspection

This research introduces an AI Vision-based Robotic System (AVRS) for industrial inspection, integrating AI, 3D vision, and robotics to enhance inspection processes. It employs advanced algorithms like Graph Neural Networks and 3D cameras to address limitations in current systems. The proposed system improves efficiency, accuracy, and automation while offering benefits such as detailed inspections and reduced manual labor. AVRS has potential to significantly enhance inspections across industries through cost-effective hardware and an interactive dashboard. This project aims to demonstrate feasibility and effectiveness, paving the way for implementation in various sectors.

**Project: AI-Enhanced Robotic Inspection System**

**Objective:**
Developing an AI Vision-based Robotic System (AVRS) for industrial inspection, integrating AI, robotics, and 3D vision technology to revolutionize inspection processes.

**Architecture Overview:**
1. **Enterprise Layer:**
   - Dashboard app for user control and parameter monitoring.
   - User authentication system for authorized access.
   - Database to store information about robots, models, and objects.

2. **AI Module (Layer 2):**
   - Processes captured images through a segmentation module.
   - Utilizes AI algorithms to identify and classify objects.
   - Stereoscopic cameras and sensors (LiDAR, encoders) aid in navigation and data capture.

3. **Motion Control Layer (Layer 3):**
   - Controls robot's path navigation.
   - VESC motor controller controls motor speed and direction.
   - Motors enable precise navigation based on AI module's output.

4. **Perception Layer (Layer 4):**
   - Detects and understands surroundings.
   - Segmentation module separates objects for improved recognition.

5. **Data Layer (Layer 5):**
   - Gathers data from robot's sensors and components.

**Hardware Components:**
- Nvidia Jetson TX2: Computing platform for AI module and image processing.
- ZED and Intel RealSense Depth Camera D435i: Capture images and depth information.
- Motors: Control robot's movement.
- VESC: Controls motor speed and direction.

**Software Components:**
- ROS2 (Robotic Operating System): Facilitates communication between hardware and software components.
- ROS packages: ros2 control, robot state publisher, rviz2, realsense-ros, zed-ros2-wrapper, ros2-web-bridge, ros2-control-panel.

**Outcome:**
The AVRS project aims to enhance inspection processes by integrating AI and robotics with 3D vision technology. This architecture offers improved efficiency, accuracy, and automation in inspecting objects from multiple angles.
