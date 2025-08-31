# 🚗 AGV-Project-Automama-Mechanical-Stack

AGV Automama is a custom-built autonomous ground vehicle (AGV) developed to demonstrate **driverless passenger transport** within a university campus. Designed and fabricated from scratch, it integrates mechanical, electrical, and software subsystems into a unified platform for autonomous mobility in semi-structured environments. 
In this project the mechanical development phases of the project is breifly discussed. The base framework closely resembles the framework design of autorickshaws in our campus.
Even though autorickshaws are 3 wheeler , automama was made four wheeler.

---

## 🔧 Overview

- **Vehicle Type:** 4-wheeled electric vehicle
- **Passenger Capacity:** 2 seats
- **Drive Motor:** 1 kW Brushless DC (BLDC) motor
- **Steering:** Ackermann steering geometry with servo train mechanism
- **Braking:** Linear motor actuator with resistive position feedback
- **Chassis:** Custom steel/aluminum frame with battery casing under the seats
- **Control Feedback:**
  - Rotary encoder for steering angle
  - Linear resistance module for brake position

---
<img src="media/ezgif.com-optimize.gif" alt="AGV Automama" width="600"/>


## 🛠 Mechanical Architecture

### 🔩 Chassis & Frame
- Designed for modularity and strength
- Low center-of-gravity layout for improved handling
- Reinforced seat mounting points
- Battery casing integrated under seating platform
<img src="media/IMG_20250611_183717807_MFNR (1).jpg" alt="AGV Automama" width="600"/>

### 🧭 Steering System
- Ackermann steering mechanism for real-time angle accuracy
- High-torque servo with gear train ensures fine angular control
- Rotary encoder feedback for accurate steering estimation
<img src="media/Screenshot 2025-01-03 000553.png" alt="AGV Automama" width="600"/>

### 🛑 Braking Mechanism
- Controlled by a linear electric actuator
- Feedback via linear position sensor (resistance-based)
- Allows precise braking control under programmatic logic
<img src="media/Ackermann test Rack & pinion.gif" alt="AGV Automama" width="600"/>

### 🛑 Stereo Vision frame
- Custom made stereo camera pair
- 3D printed the frame with flexible stereo camera base width of 15-20 cm.
- Camera holder frames to firmly grip the camera in vibrtion
<img src="media/WhatsApp Image 2025-07-24 at 5.23.27 PM.jpeg" alt="AGV Automama" width="600"/>

---
## 🧪 Use Cases

AGV Automama is designed for autonomous transport in:

- University Campuses
- Research Parks
- Factories & Warehouses
- Large Residential or Hospital Grounds

The 3D designs and parts are available in GrabCAD [here](https://grabcad.com/library/project-automama-1)
---

## 🚀 Roadmap & Future Work

- [ ] ROS 2-based control integration
- [ ] Obstacle avoidance with LiDAR & stereo vision
- [ ] Full autonomous waypoint navigation
- [ ] GUI dashboard for remote monitoring

---

## 📄 License

This project is part of an academic research initiative. Please contact the team for collaboration or usage.

---
