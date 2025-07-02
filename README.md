# 🚗 Bluetooth-Controlled RC Car Project

**Affiliated with KL Deemed to be University, Green Fields, Vaddeswaram, Guntur District – 522302**

---

## 📌 Project Overview

This repository contains two Arduino-based robotics projects:

1. **🔧 Basic Bluetooth RC Car** – A manually controlled robot via Bluetooth using a smartphone app.
2. **🤖 Autonomous RC Car with Obstacle Avoidance** – An enhanced version that integrates an ultrasonic sensor for semi-autonomous behavior.

These projects were developed to explore embedded systems, wireless communication, and robotics in a practical, educational setting.

---

## 📄 Abstract

Bluetooth technology is transforming the way electronic devices interact, enabling real-time wireless control and automation. This project applies Bluetooth communication to remotely control an RC car, with two functional versions:

- A **basic model** offering manual control via a smartphone
- An **autonomous version** using an ultrasonic sensor for obstacle detection and avoidance

The project integrates Arduino hardware with motor drivers and sensors to demonstrate core robotics concepts. It emphasizes learning through hands-on experimentation, contributing to areas like **STEM education**, **mobility automation**, and **wireless control systems**.

---

## 🧠 Keywords

- Bluetooth  
- Remote Control  
- Wireless Communication  
- Arduino  
- Obstacle Avoidance  
- Automation  
- Embedded Systems  
- Robotics  
- STEM Education  
- Mobility

---

## 🧾 Table of Contents

- [1. Basic Bluetooth RC Car](#1-basic-bluetooth-rc-car)
- [2. Autonomous RC Car with Obstacle Avoidance](#2-autonomous-rc-car-with-obstacle-avoidance)
- [Hardware Requirements](#hardware-requirements)
- [Software Components](#software-components)
- [Circuit Diagrams](#circuit-diagrams)
- [Results](#results)
- [Conclusion](#conclusion)
- [References](#references)
- [Acknowledgements](#acknowledgements)
- [License](#license)

---

## 🎮 1. Basic Bluetooth RC Car

This version allows directional control of the car via Bluetooth using a smartphone app. Commands like `F`, `B`, `L`, `R`, and `S` are sent via serial to control motor directions using the L293D driver.

### 🔧 Features
- Real-time manual control
- Compatible with Android Bluetooth controller apps
- Modular Arduino-based design
- Customizable pin configuration and speed

---

## 🤖 2. Autonomous RC Car with Obstacle Avoidance

This upgraded version integrates an **HC-SR04 ultrasonic sensor** to detect and avoid obstacles automatically. It operates in hybrid mode: Bluetooth control + intelligent stopping/turning when obstacles are nearby.

### 🧠 Additional Features
- Real-time distance measurement
- Dynamic stopping or steering logic
- Enhanced interactivity and safety
- Smart movement in limited environments

---

## 🧰 Hardware Requirements

| Component                          | Quantity |
|-----------------------------------|----------|
| Arduino UNO                       | 1        |
| Bluetooth Module (HC-05)          | 1        |
| L293D Motor Driver                | 1        |
| DC Gear Motors + Wheels           | 4        |
| Ultrasonic Sensor (HC-SR04)       | 1 *(Autonomous only)* |
| Robot Chassis                     | 1        |
| Battery + Holder (6V–12V)         | 1        |
| Jumper Wires                      | Several  |

---

## 💻 Software Components

- Arduino IDE  
- Bluetooth Terminal App (e.g., "Bluetooth RC Controller")  
- Serial communication handling  
- PWM motor speed control  
- Sensor input processing (for autonomous mode)  
- App-to-Arduino command mapping  
- Real-time feedback and response logic

---

## 🖥️ Circuit Diagrams

> *(Upload your diagrams to `/images/` and link them below)*

- **Basic RC Car Circuit**  
  ![Bluetooth RC Car Circuit](images/bluetooth_rc_circuit.png)

- **Autonomous RC Car Circuit**  
  ![Autonomous RC Circuit](images/autonomous_rc_circuit.png)

---

## 📈 Results

### ✅ Basic Version:
- Full directional control (forward, reverse, left, right)
- Smooth operation via Bluetooth from smartphone
- Ideal for beginner learning and hobby robotics

### ✅ Autonomous Version:
- Detects objects within 10–15 cm
- Automatically stops or steers around obstacles
- Semi-autonomous behavior while retaining Bluetooth control
- Great demonstration of sensor-based decision-making

---

## 📘 Conclusion

The Bluetooth-Controlled RC Car project showcases how embedded systems, mobile communication, and robotics can converge into a hands-on learning platform. The **basic model** allows students and hobbyists to understand serial communication and motor control, while the **autonomous version** introduces concepts like sensor integration, real-time decision-making, and automation.

Both models serve educational, experimental, and recreational purposes and pave the way for future smart mobility innovations.

---

## 🎥 References

- [🔧 Arduino 4WD Robot Chassis Kit Assembly](https://youtu.be/fuEPApoblwo?si=Vs-afMRCmn8TI9B8)  
- [📱 Arduino 4WD Bluetooth Controlled Robot Car Step by Step](https://youtu.be/J4gonNap9EM?si=lVMiDdp0KJt1l1G6)  
- [🧠 Obstacle Avoiding Robot Car](https://youtu.be/J3WN_XWuR8g?si=uP3V66sG6Z71jA61)

---

## 🙏 Acknowledgements

We would like to express our sincere gratitude to the faculty of **KL Deemed to be University** for their continuous support and mentorship throughout this project. Their guidance made both versions of the project successful and enriching.

**Contributors:**
- **M. Satish** – 2200049079  
- **K. Ranga Nitheesh** – 2200049143  

---

## 🛠️ License

This project is shared for **educational and non-commercial use**. You are welcome to fork and improve it. Please give credit to the original authors and contributors.

---
