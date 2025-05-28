# Advanced-Hydrophonic-Plant-Growth-Chamber
## 📘 Overview
This project presents an intelligent, automated hydroponic system designed for sustainable urban agriculture. Leveraging ESP32, a suite of sensors, and an IoT-enabled interface, the system autonomously maintains optimal growing conditions for plants minimizing manual intervention while maximizing yield and resource efficiency.
The project targets key global challenges such as water scarcity, climate unpredictability, and limited arable land, offering a smart, scalable, and sustainable solution for modern agriculture.

## 🎯 Objectives
- Automate control of pH, nutrient concentration, light, humidity, and temperature.
- Monitor real-time environmental parameters with sensor feedback.
- Provide user interaction via web dashboard hosted on ESP32.
- Enable cloud integration and remote access.
- Achieve water-efficient and soil-free farming using hydroponic principles.
  
## 🧠 System Features
- 🌡️ Temperature & Humidity Monitoring (DHT22)
- 💧 pH and EC Regulation for nutrient balance
- 🔦 LED Grow Light Control with simulated daylight cycle
- 🚿 Automated Watering and Nutrient Circulation
- 🌬️ Ventilation Fans for humidity and airflow control
- 🌐 Wi-Fi-enabled Web Dashboard (local server)
- 🔋 Energy-efficient and scalable design (Solar-ready)
  
## 🔧 Hardware Used
Component	Description
- ESP32	- IoT microcontroller with Wi-Fi
- DHT22 Sensor -	Temperature and humidity monitoring
- pH Sensor	- Monitors nutrient solution acidity
- EC/TDS Sensor -	Measures nutrient concentration
- Water Level Sensor - Ensures sufficient nutrient levels
- LED Grow Lights	Simulates sunlight for photosynthesis
- Relay Modules	Control actuators
- Water Pumps	Circulate nutrient solution
- Ventilation Fans	Regulate humidity and air quality
- Power Supply	5V/12V regulated for all components

## 💻 Software & Tools
- Arduino IDE (ESP32 Programming)
- HTML/CSS + JavaScript (Web UI)
- MQTT / HTTP Protocols (Communication)
- Firebase/ThingSpeak (optional for cloud monitoring)
- JSON / AJAX (Real-time data fetch)
- Excel/CSV Logs (Sensor data tracking)

🌍 Sustainability Highlights
♻️ Up to 90% less water usage compared to soil farming

☀️ Solar panel integration supported (future enhancement)

🐞 No pesticide usage due to controlled environment

📈 Faster plant growth (30–50%) via optimized control

🧪 Real-time analytics and trend logs

🧪 Testing Summary
🌿 Plant: Tulsi (Ocimum tenuiflorum)

📆 Duration: 35 Days

🔍 Observations:

30% water saved

25% faster growth rate

Stable environmental control

📉 Comparative Analysis: Outperforms soil-based method in efficiency, control, and yield

🧰 How to Use
Connect ESP32 to your PC and upload the Arduino code.

Access dashboard via device’s Wi-Fi hotspot (192.168.1.1).

Monitor and control:

pH

Temperature

Light intensity

Water level

Adjust settings or switch between Auto/Manual mode via web interface.

Optional: Connect to cloud for remote access and logs.

🚧 Challenges Overcome
Signal interference resolved via logic converters and shielding

Power stability achieved with regulated 12V/5A supply

Web interface optimized for low memory footprint

Sensor calibration ensured accuracy (pH buffers, TDS standards)

📈 Future Enhancements
🌞 Solar panel integration for off-grid operation

🤖 AI/ML-based predictive control and anomaly detection

🌿 Multi-crop profiles and intelligent scheduling

📲 Cloud dashboard and mobile app version
