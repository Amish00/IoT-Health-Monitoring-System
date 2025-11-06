# 🩺 IoT Based Health Monitoring System

An IoT-powered wearable device designed to monitor vital health parameters in real time — ideal for elderly care and remote health tracking. The system combines multiple sensors with cloud connectivity to provide continuous monitoring, alerts, and remote data visualization.

---

## 🚀 Overview
The **IoT Based Health Monitoring System** integrates the **ESP32** microcontroller with the **MAX30102** (heart rate & SpO₂), **MLX90614** (body temperature), and **NEO6M GPS** (location tracking) sensors.  
All collected data is displayed locally on an **OLED screen** and transmitted to the **Arduino Cloud dashboard** for real-time monitoring by caregivers or healthcare professionals.

If abnormal readings are detected, the system sends an instant **WhatsApp alert** via the **CallMeBot API**, including the patient’s latest readings and GPS coordinates — ensuring timely medical response.

---

## ⚙️ Features
- Real-time monitoring of heart rate, SpO₂, temperature, and location  
- OLED display for on-device visualization  
- Cloud-based remote monitoring through **Arduino Cloud Dashboard**  
- **WhatsApp alerts** via **CallMeBot** for abnormal readings  
- Compact, battery-powered wearable design  
- Ideal for **elderly care** and remote health supervision  

---

## 🧠 Components Used
- **ESP32** – Main microcontroller  
- **MAX30102** – Heart rate & SpO₂ sensor  
- **MLX90614** – Non-contact temperature sensor  
- **NEO6M GPS** – Location tracking module  
- **OLED Display (0.96")** – Health data visualization  
- **Li-ion Batteries (7.4V)** – Portable power supply  

---

## ☁️ Software and Tools
- **Arduino IDE** for programming  
- **Arduino Cloud** for dashboard visualization  
- **CallMeBot API** for WhatsApp notifications  
- Libraries: `MAX3010x`, `Adafruit_MLX90614`, `TinyGPS++`, `SSD1306`, `GFX`  

---

## 🧩 Future Enhancements
- AI-based predictive analytics for early risk detection  
- Integration with Electronic Health Records (EHR)  
- Mobile caregiver app for two-way communication  
- Longer battery life and solar charging options  

---

## 👥 Contributors
- Sujal Bajracharya  
- Pranish Raj Tuladhar  
- Amish Man Joshi  
- Raman Kayastha  
- Saliv Maharjan  

---

## 🏫 Institution
**Virinchi College** – School of Science and Technology  
**Bachelor of Information & Communication Technology (BICT)**  

---

## 🩸 Keywords
`IoT` · `ESP32` · `Arduino` · `MAX30102` · `MLX90614` · `NEO6M GPS` · `Elderly Care` · `Health Monitoring` · `CallMeBot` · `Arduino Cloud`
