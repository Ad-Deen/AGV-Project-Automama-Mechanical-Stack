# AGV-Project-Automama-Mechanical-Stack

# 🚗 AGV Automama — Autonomous Campus Transport Vehicle

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

## 🛠 Mechanical Architecture

### 🔩 Chassis & Frame
- Designed for modularity and strength
- Low center-of-gravity layout for improved handling
- Reinforced seat mounting points
- Battery casing integrated under seating platform

### 🧭 Steering System
- Ackermann steering mechanism for real-time angle accuracy
- High-torque servo with gear train ensures fine angular control
- Rotary encoder feedback for accurate steering estimation

### 🛑 Braking Mechanism
- Controlled by a linear electric actuator
- Feedback via linear position sensor (resistance-based)
- Allows precise braking control under programmatic logic

---

## ⚡ Electrical System

- **Motor Driver:** High-power BLDC driver with programmable inputs
- **Battery Enclosure:** Secure, thermally insulated and shock-absorbing
- **Control System:** Feedback-driven microcontroller loop (future ROS 2 integration)

---

## 📈 Sensor Integration

| Module                  | Purpose                         |
|-------------------------|----------------------------------|
| Rotary Encoder          | Real-time steering feedback      |
| Linear Resistance Sensor| Brake actuator position feedback |
| IMU & GPS *(optional)*  | Navigation & pose estimation     |

---

## 🧪 Use Cases

AGV Automama is designed for autonomous transport in:

- University Campuses
- Research Parks
- Factories & Warehouses
- Large Residential or Hospital Grounds

---

## 🚀 Roadmap & Future Work

- [ ] ROS 2-based control integration
- [ ] Obstacle avoidance with LiDAR & stereo vision
- [ ] Full autonomous waypoint navigation
- [ ] GUI dashboard for remote monitoring

---

## 📷 Media & Diagrams

> *(Insert images, wiring diagrams, and mechanical drawings here)*

---

## 👥 Credits

**Project Lead:** Ad-Deen Mahbub  
**Affiliation:** [Your University Name]  
**Team:** Undergraduate engineering researchers  
**Timeline:** Prototype complete; testing in progress

---

## 📄 License

This project is part of an academic research initiative. Please contact the team for collaboration or usage.

---
