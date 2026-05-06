AI–IoT Based Smart Stove for Enhanced Safety

**Project Overview**
An AI and IoT integrated smart stove safety system that uses Deep Learning and embedded hardware to prevent kitchen accidents caused by children and LPG gas leakages.

**Features**
1) Real-time age detection using CNN algorithm
2) Auto turn off stove knob if person age is less than 7
3) LPG gas leakage detection using gas sensor
4) Auto shut off cylinder valve on gas detection
5) Live camera feed processing using OpenCV

**Technologies Used**
**Category**          **Tools / Technologies** 
Programming Language     Python
Deep Learning            CNN (Convolutional Neural Network)
Computer Vision          OpenCV
Hardware                 Arduino 
Actuators                Servo Motor x2
Sensor                   Gas Sensor (MQ-2 / MQ-6)
Domain                   IoT, Embedded Systems, AI

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

### 🧒 Child Detected — Stove Auto Lock
![Child Detection](images/child_detection.jpg)
> Age (4–6) detected → Cmd: LOCK → Servo motor turns OFF stove knob

### 👩 Adult Detected — Stove Remains ON
![Adult Detection](images/adult_detection.jpg)
> Age (38–43) detected → No action → Stove remains ON

### 🔌 Circuit Diagram
![Circuit Diagram](images/circuit_diagram.jpg)
> Arduino UNO + MQ Gas Sensor + Servo Motor + Buzzer + LED

**Author**

| Field | Details |
|---|---|
| **Name** | K Siri Chandana Lakshmi Priyanka |
| **Degree** | B.Tech / B.E. |
| **College** | BVRIT Hyderabad College of Engineering for Women |
| **Email** | keellasirichandana0@gmail.com |
| **LinkedIn** | [linkedin.com/in/keella-siri-chandana](https://www.linkedin.com/in/keella-siri-chandana-lakshmi-priyanka-166654259/) |

**License**
This project is open source and available under the [MIT License](LICENSE).







