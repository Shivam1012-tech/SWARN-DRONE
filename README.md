# 🛩️ SkyFlock Drone Mission – Shivam Kushwaha

## 📌 Overview

This repository contains my submission for the SkyFlock Uaviation Pvt. Ltd. Technical Internship – ROS Drone Swarm Simulation & Control.

The project builds on the existing single-drone simulation codebase and adds a new autonomous mission using ROS 2 and PX4.

---

## ✅ Missions Implemented

- 🚁 **Single Drone Autonomous Flight**
  - Takeoff to 3m altitude
  - Fly in a square pattern across 4 waypoints
  - Return to launch and land

---

## 🧠 Summary of Changes

| File                          | Purpose                                 |
|------------------------------|------------------------------------------|
| `missions/drone_mission.py`  | Python node for waypoint flight mission |
| `launch/drone_mission.launch.py` | Launch file for the mission         |
| `README.md`                  | Documentation and submission details     |
| `setup.py`                   | ROS 2 Python package setup               |

---

## 🚀 How to Run

### 🧱 Build the workspace

```bash
cd ~/swarm_drone
colcon build
source install/setup.bash


## DEMO VIDEO LINK
https://youtu.be/_JQag2kLl4o
