**AI-IoT-Based-Smart-Stove-for-Enhanced-Safety**


**Project Overview**

An AI and IoT integrated smart stove safety system that uses Deep Learning and embedded hardware to prevent kitchen accidents caused by children and LPG gas leakages.

**Features**

1) Real-time age detection using CNN algorithm
2) Auto turn off stove knob if person age is less than 7
3) LPG gas leakage detection using gas sensor
4) Auto shut off cylinder valve on gas detection
5) Live camera feed processing using OpenCV

**Technologies Used**
         **Tools / Technologies** 

Python, CNN (Convolutional Neural Network), OpenCV, Arduino , Servo Motor x2, Gas Sensor (MQ-2 / MQ-6), IoT, Embedded Systems, AI

**How It Works**

**Module 1 – Child Safety (Age Detection)**

1)Live camera captures real-time video
2)CNN model detects and estimates person's age
3)If age < 7 → Servo Motor 1 turns OFF the stove knob
4)If age > 7 → Stove remains ON normally

**Module 2 – Gas Leakage Safety**

1)Gas sensor monitors LPG cylinder continuously
2)If gas leakage detected → Signal sent to Servo Motor 2
3)Servo Motor 2 automatically shuts the cylinder valve

**Requirements**

Python 3.x
OpenCV
TensorFlow / Keras
NumPy
Serial (PySerial)

 **How to Run**
1. Clone the repository
   git clone https://github.com/yourusername/AI-IoT-Smart-Stove-Safety-System

2. Install dependencies
   pip install -r requirements.txt

3. Run age detection module
   python age_detection.py

4. Run gas sensor module
   python gas_sensor.py

## 📷 Project Screenshots

###  Child Detected — Stove Auto Lock

<img width="357" height="274" alt="Screenshot 2026-05-06 120659" src="https://github.com/user-attachments/assets/a313c816-c0e0-4304-a5f3-cd04a85b6d9d" />

> Age (4–6) detected → Cmd: LOCK → Servo motor turns OFF stove knob

###  Adult Detected — Stove Remains ON
<img width="497" height="347" alt="Screenshot 2025-06-10 165317" src="https://github.com/user-attachments/assets/45b6360b-05bb-436c-a49a-5c231b0dd700" />

> Age (38–43) detected → No action → Stove remains ON

###  Circuit Diagram
<img width="984" height="733" alt="Screenshot 2025-06-03 161308" src="https://github.com/user-attachments/assets/994f6324-3d3b-44d9-b830-4dc17acd1c65" />

> Arduino UNO + MQ Gas Sensor + Servo Motor + Buzzer + LED

**Author**

| Field | Details |
|---|---|
| **Name** | K Siri Chandana Lakshmi Priyanka |
| **Degree** | B.Tech / B.E. |
| **College** | BVRIT Hyderabad College of Engineering for Women |
| **Email** | keellasirichandana03@gmail.com |
| **LinkedIn** | [linkedin.com/in/keella-siri-chandana](https://www.linkedin.com/in/keella-siri-chandana-lakshmi-priyanka-166654259/) |

**License**
This project is open source and available under the [MIT License](LICENSE).







