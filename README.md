# 🌱 Grounded - Edge-AI Smart Agriculture System

**Real-time NPK estimation + Crop Recommendation in under 5 seconds**  
**Fully offline • Reagent-free • TinyML on ESP32 • Cost < ₹1,300**

![Dashboard Preview](images/dashboard.png)

## ✨ Features
- Optical proxy NPK sensing with **TCS3200** spectral color sensor
- Capacitive soil moisture sensor + **moisture-aware sensor fusion**
- **Quantized Random Forest** running 100% on-device (TinyML)
- Self-hosted Wi-Fi hotspot (`Grounded_Lab`) + beautiful mobile dashboard
- Transistor-switched power → sensor lifespan > 3 years
- Zero internet, zero cloud, zero reagents

## 📊 Performance
- Accuracy: **89.3%** (4-feature model)
- Inference time: **< 2 ms**
- End-to-end latency: **≈5 seconds**

## 🛠️ Hardware (Total Cost: ₹1,290)

See [hardware/BOM.md](hardware/BOM.md)

## 🚀 Quick Start

1. Clone the repo
2. Open `src/Grounded.ino` in Arduino IDE
3. Install libraries: **WebServer** and **ArduinoJson**
4. **Calibrate** your black-box (very important!)
5. Upload to ESP32
6. Connect your phone to Wi-Fi `Grounded_Lab` (password: `password123`)
7. Open `192.168.4.1` in browser → Login → Start scanning!

## 📁 Project Structure
