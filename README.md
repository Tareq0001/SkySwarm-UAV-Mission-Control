# SKY-SWARM GCS | Autonomous UAV Swarm Command & BVLOS Mission Control

[![Live Demo](https://img.shields.io/badge/Live_Demo-GitHub_Pages-blue?style=for-the-badge&logo=github)](https://tareq0001.github.io/SkySwarm-UAV-Mission-Control/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

**SKY-SWARM GCS** is an enterprise-grade tactical Ground Control Station (GCS) and autonomous fleet operations workstation for multi-UAV drone swarms executing Beyond Visual Line of Sight (BVLOS) missions.

---

## ⚡ Core Aerospace & Fleet Management Systems

1. **Autonomous Swarm Guidance & Flocking:**
   - Distributed Reynolds Flocking Model: Separation, Alignment, Cohesion, and Obstacle Avoidance.
   - Artificial Potential Fields for dynamic mid-air collision avoidance.
   - Real-time formation switching: V-Shape, Grid Search, Perimeter Escort, and Sweep Line.
   - Scalable from 6 to 32 autonomous drones.

2. **MAVLink 2.0 Telemetry Bus:**
   - Real-time simulation of `HEARTBEAT`, `GLOBAL_POSITION_INT`, `ATTITUDE`, `SYS_STATUS`, and waypoint command sequencing.
   - CRC-verified packet streaming and logging.

3. **BVLOS Tactical Operations & Fail-Safe Matrix:**
   - Interactive tactical 2D/3D radar display with concentric range rings and polygon geofences.
   - Dynamic Return-To-Home (RTH) reserve battery calculation accounting for opposing winds.
   - Lost-Link state machine with autonomous fail-safe triggers.
   - Airspace deconfliction (UTM / ADS-B In receiver).

4. **Dual FLIR / EO Thermal Camera Gimbal:**
   - Real-time simulated FLIR infrared sensor feed.
   - Autonomous AI object detection with bounding-box target tracking.
   - Laser rangefinder distance readout.

5. **Photogrammetry & Survey Automation:**
   - 80% Forward / 75% Side overlap automatic calculations.
   - Ground Sampling Distance (GSD) estimator (1.8 cm/px).

---

## 🚀 Live Demo

Access the Ground Control Station: [https://tareq0001.github.io/SkySwarm-UAV-Mission-Control/](https://tareq0001.github.io/SkySwarm-UAV-Mission-Control/)

Developed by **Tareq Aboushi** (أ. طارق ابوعشي).
