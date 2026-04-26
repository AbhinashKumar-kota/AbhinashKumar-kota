# Kota Venkata Abhinash Kumar

**Robotics Engineer — Control Systems · Multi-Agent Systems · Real-World Deployment**

I got into robotics because I believe automation is how you compound your impact on the world — and robotics is where automation gets physical. Everything I've built has been in pursuit of one question: *how do you make a system that actually holds up when reality doesn't match the model?*

---

## What I've been building toward

**Control theory → Research → Deployment**

I didn't jump straight into robotics. I started by going deep into control — consensus algorithms, sliding mode theory, fault-tolerant architectures — because I wanted to understand the layer where system reliability is actually decided. That led me to IIT Mandi, where I implemented a decentralized consensus-based controller for two Crazyflie UAVs coordinating in a GPS-denied indoor environment. No central planner, no GPS. ~90% coordination success rate. Oscillation-free.

Then I spent six months at **Origin** as a deployment intern — because research taught me that a working algorithm in simulation is not a deployed system. I owned validation of a mobile manipulator across 100+ test sessions, debugged ROS2 perception-control pipelines under real sensor noise and latency, and built a data pipeline and dashboard that changed how the team analyzed failures.

That gap — between what works in the lab and what ships in the world — is the problem I keep coming back to.

---

## Projects

### Multi-Agent UAV Formation Control
Decentralized consensus-based controller for drone formation tracking using Crazyflie UAVs. Validated in PyBullet simulation before deploying on physical hardware in GPS-denied conditions. Achieved stable coordination using onboard sensing only — no oscillations, no central planner.

### Fault-Tolerant UUV Control &nbsp;·&nbsp; [→ Repo](https://github.com/AbhinashKumar-kota/Passive-Fault-Tolerant-Control-UUV)
Fast Terminal Sliding Mode Control (FTSMC) for an Underwater Unmanned Vehicle under 50–100% actuator faults. The system maintained trajectory tracking where a baseline PID controller crashed. Fault recovery without manual intervention.

### Bio-Inspired Swarm Coordination (BMO Framework) &nbsp;·&nbsp; [→ Repo](https://github.com/AbhinashKumar-kota/bmo_ws)
Decentralized multi-agent coordination framework using bio-inspired optimization. Collision-free behavior across agents using only local rules — no global planner required.

### ArUco Marker-Based Robot Navigation
Real-time pose estimation and closed-loop navigation using OpenCV ArUco detection. ~90% detection accuracy at 10 FPS on embedded hardware. Used for position feedback in robot control.

---

## Skills

```
Control         PID · Sliding Mode Control · Consensus Control · Fault-Tolerant Control
Robotics        ROS2 · Crazyflie · PyBullet
Perception      OpenCV · ArUco detection · Pose estimation
Languages       Python · C++ · C
Hardware        Arduino · ESP32 · Raspberry Pi
Tools           NumPy · Matplotlib · Git
```

---

## Currently

- Final year, B.Tech Electrical Engineering — RGUKT Nuzvid (GPA: 8.27)
- Looking for robotics engineering roles in control, deployment, or multi-agent systems

---

## Reach me

[abhinashkota@gmail.com](mailto:abhinashkota@gmail.com) &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/abhinash) &nbsp;·&nbsp; +91-6303081215
