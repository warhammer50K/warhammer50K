# Jaeyeol Song

**Robotics Engineer — LiDAR SLAM · Autonomous Navigation · Multi-Agent Fleet Systems**

<p align="center">
  <img src="assets/handheld-slam-map.png" height="150" alt="LiDAR point cloud map"/>
  <img src="assets/hero-2.png" height="150" alt="AMR fleet in logistics center"/>
  <img src="assets/hero-3.png" height="150" alt="2D SLAM multi-agent map"/>
</p>

I build autonomous mobile robot systems end to end — from LiDAR-inertial SLAM and localization to fleet-level coordination. I implement SLAM front-ends and back-ends from the equations up — ESIKF, on-manifold optimization, analytically derived ICP Jacobians — and I'm currently working on degeneracy-aware LiDAR-inertial odometry for solid-state sensors.

In industry since 2022: 30+ AMRs deployed across a 23,000 m² logistics center, precision drilling automation for aerospace manufacturing, and a handheld 3D mapping device built from the ground up.

Based in Daejeon, South Korea.

---

## Selected Work

### HandheldSLAM <sub>(private)</sub>

Handheld 3D mapping device with real-time LiDAR SLAM for large-scale environments — custom hardware and the full software pipeline.

<p>
  <img src="assets/handheld-slam.png" height="160" alt="HandheldSLAM device"/>
  <img src="assets/handheld-slam-map.png" height="160" alt="HandheldSLAM mapping result"/>
</p>

### [WebPointCloud](https://github.com/warhammer50K/WebPointCloud)

Web-based 3D point cloud viewer and analysis tool. No install, runs in the browser — LAS, LAZ, PLY, PCD, XYZ, PTS.

<img src="assets/webpointcloud.png" width="420" alt="WebPointCloud viewer"/>

### [sam2-oakd-realtime](https://github.com/warhammer50K/sam2-oakd-realtime)

Real-time object segmentation with Meta SAM 2.1 on an OAK-D Lite, served via FastAPI.

### [blackfly-gige-viewer](https://github.com/warhammer50K/blackfly-gige-viewer)

FLIR Blackfly GigE camera viewer built on the Spinnaker SDK, C++17.

### [UDPCOMM](https://github.com/warhammer50K/UDPCOMM)

Single-header, dependency-free C++11 library for exchanging plain structs over UDP — typed send/receive, framing, background receive thread. Born from joystick-to-robot teleoperation.

▶ Robots in action: [YouTube @SJY_Robotics](https://www.youtube.com/@SJY_Robotics)

---

## Industry (2022–present)

- **Warehouse AMR fleet** — 30+ robots in a 23,000 m² logistics center: SLAM-based localization, autonomous navigation, multi-agent path finding, and the fleet management system coordinating them.
- **Aerospace manufacturing** — precision drilling automation.
- **3D vision** — structured light, depth camera calibration, real-time segmentation, robotic shoe bonding.
- **Platforms** — serving robots, AMR, mecanum-wheel platforms, AMMR (mobile manipulation).

---

## Tech

| | |
|--|--|
| **SLAM** <sub>studied / re-implemented</sub> | FAST-LIO2, LIO-SAM, Point-LIO, A-LOAM |
| **Libraries** | GTSAM, PCL, Open3D, Eigen |
| **Place Recognition** | Scan Context |
| **Vision** | OpenCV, Meta SAM 2.1, Zivid SDK |
| **Hardware** | Velodyne, Livox, FLIR Blackfly, Luxonis OAK-D, u-blox GPS |
| **Stack** | C++, Python, ROS, Qt, Docker, Linux |

---

## Contact

[pixvnt151@gmail.com](mailto:pixvnt151@gmail.com) · [YouTube](https://www.youtube.com/@SJY_Robotics) · Daejeon, South Korea
