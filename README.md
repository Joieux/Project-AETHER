# Project AETHER: Distributed AI & Robotics Reconnaissance

**Status:** Prototype / Research Phase
**Focus:** Distributed Systems, Edge AI, SIGINT, Autonomous Navigation

![Project AETHER Architecture](https://github.com/Joieux/Project-AETHER/blob/main/aether.jpg?raw=true)
*(Note: If you uploaded the image 'aether.jpg', it will appear above. If not, delete this line)*

## 📄 [Click Here to View the Full Architecture & Roadmap (PDF)](./AETHER_Distributed_Robotics.pdf)

---

## 🔍 Executive Summary
Project AETHER is a distributed robotics system designed to separate "action" from "thought." [cite_start]It utilizes a **"Hive Mind" architecture** [cite: 53] [cite_start]where a lightweight mobile scout (Petoi Bittle) handles sensory data, while a stationary heavy-compute cluster (Jetson Orin + Raspberry Pi Swarm) handles logic, SLAM mapping, and AI inference[cite: 54, 55].

This approach allows for sophisticated reconnaissance capabilities without weighing down the mobile agent.

## 🛠️ Tech Stack & Hardware
* [cite_start]**Orchestration:** K3s (Kubernetes), ROS2 Humble [cite: 72]
* [cite_start]**AI & Vision:** NVIDIA Isaac ROS (Visual SLAM), YOLOv8 (Object Detection) [cite: 73]
* [cite_start]**Compute Node:** NVIDIA Jetson Orin Nano (Hive Mind Brain) [cite: 68]
* [cite_start]**Mobile Agent:** Petoi Bittle X (bionic robot dog) [cite: 69]
* [cite_start]**SIGINT:** RTL-SDR / Fox Hunt Radio for RF Triangulation [cite: 70, 87]

## 🎯 Key Capabilities
1.  [cite_start]**Visual SLAM Mapping:** Autonomous navigation in unknown environments[cite: 120].
2.  [cite_start]**Fox Hunting (SIGINT):** Ability to triangulate and locate RF signals (emergency beacons or interference)[cite: 146, 166].
3.  [cite_start]**Local LLM Control:** Voice command interpretation running entirely on the edge (no cloud dependency)[cite: 139, 140].

---
*Created by Joyce Johnson | Cybersecurity Analyst & Researcher*
