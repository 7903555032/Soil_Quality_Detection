# 🌱 Smart Soil Quality Detection System with AI-Powered Recommendations

This repository contains the complete source code, documentation, and resources for the **Attachable Smart Soil Analysis Device** developed as part of an academic project under the Department of Electronics and Communication Engineering, Birla Institute of Technology, Patna.

## 📌 Overview

A real-time, field-deployable soil testing and recommendation system designed to empower farmers through data-driven agriculture. The system integrates a multi-sensor device with an AI-powered recommendation engine and a mobile application.

## 🎯 Objectives

- Measure 7 key soil parameters: **Nitrogen (N), Phosphorus (P), Potassium (K), pH, Moisture, EC, TDS**
- Analyze soil health in real-time with **ESP32-S3 microcontroller**
- Generate AI-driven crop and fertilizer recommendations
- Provide results via an intuitive **mobile app** with multi-language and voice support
- Enable **affordable soil testing (< ₹85 per test)** and improve fertilizer efficiency

## 🧠 AI Recommendation Engine

- Uses a **3-layer neural network** trained on 15,000+ soil samples
- Inputs: soil parameters, GPS location, crop type, weather forecast
- Outputs:
  - ✅ Fertilizer dosage (NPK ratio)
  - ✅ Suitable crops with yield potential
  - ✅ Soil health improvement tips

## 🧰 Tech Stack

### Hardware
- ESP32-S3 (240MHz, WiFi/BLE)
- NPK Sensor Module
- pH Sensor
- Capacitive Moisture Sensor
- EC/TDS Sensor
- GPS Module (Neo-6M)
- IP54-rated 3D Printed Enclosure

### Software
- **Firmware:** Arduino + BLE + OTA updates
- **Mobile App:** Flutter + TensorFlow Lite
- **Cloud Backend:** Firebase Firestore + Analytics Dashboard

## 📲 Mobile Application Features

- Real-time soil report
- Fertilizer & crop recommendation
- Voice support in English, Hindi, and regional languages
- Offline functionality with cloud sync
- Graphical data visualization & history

## 📊 Validation Results

| Metric                 | Target      | Achieved |
|------------------------|-------------|----------|
| Measurement Accuracy   | > 85%       | ✅       |
| Analysis Time          | < 30 sec    | ✅       |
| Battery Life           | > 8 hours   | ✅       |
| Farmer Adoption Rate   | > 70%       | ✅       |
| Cost Reduction         | > 90%       | ✅       |

## 💡 Innovation Highlights

- 🔄 **Hybrid Sensing:** Combines electrochemical + optical techniques
- ⚙️ **Edge AI:** On-device neural network for recommendations
- 🌐 **Bluetooth/WiFi + GPS Integration**
- 🗣️ **Voice UI** for digitally underserved farmers
- 🧠 **Self-calibration** algorithms for field drift correction

## 📅 Timeline Snapshot (24 Months)

1. ✅ Hardware design and prototyping
2. ✅ ML training and app development
3. ✅ Lab and field testing across agro-zones
4. 🔄 Feedback integration and optimization
5. 📢 Final deployment & research publication

## 📂 Folder Structure

