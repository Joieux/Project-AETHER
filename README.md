# Project AETHER: Distributed AI & Robotics Reconnaissance

**Status:** Prototype / Research Phase
**Focus:** Distributed Systems, Edge AI, SIGINT, Autonomous Navigation

![Project AETHER Architecture](https://github.com/Joieux/Project-AETHER/blob/main/aether.png?raw=true)


## 📄 [Click Here to View the Full Architecture & Roadmap (PDF)](./AETHER_Distributed_Robotics.pdf)

---

## 🔍 Executive Summary
Project AETHER is a distributed robotics system designed to separate "action" from "thought." It utilizes a **"Hive Mind" architecture** where a lightweight mobile scout (Petoi Bittle) handles sensory data, while a stationary heavy-compute cluster (Jetson Orin + Raspberry Pi Swarm) handles logic, SLAM mapping, and AI inference.

This approach allows for sophisticated reconnaissance capabilities without weighing down the mobile agent.

## 🛠️ Tech Stack & Hardware
* **Orchestration:** K3s (Kubernetes), ROS2 Humble
* **AI & Vision:** NVIDIA Isaac ROS (Visual SLAM), YOLOv8 (Object Detection)
* **Compute Node:** NVIDIA Jetson Orin Nano (Hive Mind Brain)
* **Mobile Agent:** Petoi Bittle X (bionic robot dog)
* **SIGINT:** RTL-SDR / Fox Hunt Radio for RF Triangulation

## 🎯 Key Capabilities
1.  **Visual SLAM Mapping:** Autonomous navigation in unknown environments.
2.  **Fox Hunting (SIGINT):** Ability to triangulate and locate RF signals (emergency beacons or interference).
3.  **Local LLM Control:** Voice command interpretation running entirely on the edge (no cloud dependency).

---
*Created by Joyce Johnson | Cybersecurity Analyst & Researcher*
