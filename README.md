# IoT Smart Glove for Assistive Communication

## 📖 Project Overview
This project presents the design and implementation of an IoT-enabled smart glove developed to assist individuals with hearing, speech, or movment disabilities.

The system uses flex sensors to detect finger bending and an MPU6050 sensor to measure hand orientation. Sensor data is processed using Arduino Nano and transmitted via ESP8266-01 WiFi module to the ThingSpeak cloud platform for real-time monitoring and visualization.

The system works using predefined gesture mapping and numeric sensor readings.

---

## 🎯 Objectives
- Capture finger bending using flex sensors.
- Process sensor values using Arduino Nano.
- Transmit data via WiFi using ESP8266.
- Send numeric readings to ThingSpeak cloud.
- Display predefined assistive messages.
- Enable remote monitoring.

---

## ⚙ Hardware Components
- Arduino Nano
- 5 Flex Sensors
- MPU6050 (Accelerometer & Gyroscope)
- ESP8266-01 WiFi Module
- Buzzer
- Magnetic Switch (Security)
- 10kΩ Resistors

---

## 🌐 Cloud Platform
Data is transmitted to ThingSpeak for:
- Real-time data visualization
- Graph monitoring
- Cloud storage of sensor values

Platform:
https://thingspeak.com

---

## 🔄 System Workflow
1. Flex sensors detect finger bending.
2. MPU6050 detects hand orientation.
3. Arduino Nano reads analog values.
4. ESP8266 transmits data via WiFi.
5. ThingSpeak displays real-time sensor graphs.

---

## 🖐 Gesture Mapping

| Finger | Message |
|--------|----------|
| Thumb  | Alarm |
| Index  | I need food |
| Middle | I need medical |
| Ring   | I need toilet |
| Little | I need water |

If two fingers are flexed simultaneously:
Example:
Ring + Little → "I need toilet and water"

---

## 🔐 Security Features
- Magnetic switch activation (device works only when key inserted)
- WiFi-based secure communication

---

## 📊 Output
- Numeric sensor readings
- Cloud-based graph visualization
- Predefined assistive text messages
- Alert via buzzer

---

## 🚧 Limitations
- Requires WiFi connection
- Supports predefined gestures only
- No AI-based translation

---

## 🚀 Future Improvements
- Add machine learning classification
- Add voice output
- Improve glove ergonomics
- Develop mobile application

---
This project is the exclusive property of Team (SWR). Any use, reproduction, or exploitation without prior written permission from the team is strictly prohibited and will result in appropriate legal action.

University of Technology and Applied Sciences – Ibri

Prototype:
<img width="870" height="470" alt="image" src="https://github.com/user-attachments/assets/c8355694-69d1-4bd4-beef-e7a4816a3fbe" />
[project-Smart-Glove.docx](https://github.com/user-attachments/files/25314663/project-Smart-Glove.docx)

