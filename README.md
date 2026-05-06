# 🍳 AI–IoT Based Smart Stove for Enhanced Safety


## 📌 Project Overview
An AI and IoT integrated smart stove safety system that uses 
Deep Learning and embedded hardware to prevent kitchen accidents 
caused by children and LPG gas leakages.

---

## ⚙️ Features
- 👶 Real-time age detection using CNN algorithm
- 🔌 Auto turn off stove knob if person age is less than 7
- 💨 LPG gas leakage detection using gas sensor
- 🔧 Auto shut off cylinder valve on gas detection
- 📷 Live camera feed processing using OpenCV

---

## 🛠️ Hardware & Software Components

| Category | Tools / Technologies |
|---|---|
| Programming Language | Python |
| Deep Learning | CNN (Convolutional Neural Network) |
| Computer Vision | OpenCV |
| Hardware | Arduino |
| Actuators | Servo Motor x2 |
| Sensor | Gas Sensor (MQ-2 / MQ-6) |
| Domain | IoT, Embedded Systems, AI |

---

## 🔌 How It Works

### Module 1 — Child Safety (Age Detection)
1. Live camera captures real-time video
2. CNN model detects and estimates person's age
3. If age < 7 → Servo Motor 1 turns OFF the stove knob
4. If age > 7 → Stove remains ON normally

### Module 2 — Gas Leakage Safety
1. Gas sensor monitors LPG cylinder continuously
2. If gas leakage detected → Signal sent to Servo Motor 2
3. Servo Motor 2 automatically shuts the cylinder valve

---

## 📦 Requirements
Python 3.x
OpenCV
TensorFlow / Keras
NumPy
Serial (PySerial)

---

## 🚀 How to Run

Clone the repository
git clone https://github.com/keellasirichandana03-hash/AI-IoT-Based-Smart-Stove-for-Enhanced-Safety
Install dependencies
pip install -r requirements.txt
Run age detection module
python age_detection.py
Run gas sensor module
python gas_sensor.py


---

## 📷 Project Screenshots

### 🧒 Child Detected — Stove Auto Lock
<img width="357" height="274" alt="Child Detection" 
src="https://github.com/user-attachments/assets/a313c816-c0e0-4304-a5f3-cd04a85b6d9d" />

> Age (4–6) detected → Cmd: LOCK → Servo motor turns OFF stove knob

### 👩 Adult Detected — Stove Remains ON
<img width="497" height="347" alt="Adult Detection" 
src="https://github.com/user-attachments/assets/45b6360b-05bb-436c-a49a-5c231b0dd700" />

> Age (38–43) detected → No action → Stove remains ON

### 🔌 Circuit Diagram
<img width="984" height="733" alt="Circuit Diagram" 
src="https://github.com/user-attachments/assets/994f6324-3d3b-44d9-b830-4dc17acd1c65" />

> Arduino UNO + MQ Gas Sensor + Servo Motor + Buzzer + LED

---

## 👩‍💻 Author

| Field | Details |
|---|---|
| **Name** | K Siri Chandana Lakshmi Priyanka |
| **Degree** | B.Tech / B.E. |
| **College** | BVRIT Hyderabad College of Engineering for Women |
| **Email** | keellasirichandana03@gmail.com |
| **LinkedIn** | [linkedin.com/in/keella-siri-chandana](https://www.linkedin.com/in/keella-siri-chandana-lakshmi-priyanka-166654259/) |

---

## 📄 License
This project is open source and available under the 
[MIT License](LICENSE).

---

## ⭐ Support
If you find this project helpful,
please give it a star ⭐ on GitHub!
