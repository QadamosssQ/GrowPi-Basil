# 🌿 Smart Basil Greenhouse with Raspberry Pi Zero

A compact, fully automated greenhouse for growing basil 🌱 using a Raspberry Pi Zero. The system controls watering via a peristaltic pump, monitors light and soil moisture levels, and captures time-lapse images. Data is served through a built-in lightweight server so you can access your greenhouse remotely.

## 🚀 Features

- 🌡️ Soil moisture detection with a capacitive sensor  
- 💧 Automated watering via a **peristaltic pump**  
- ☀️ Light level monitoring with a light sensor  
- 💡 LED grow light control when ambient light is low  
- 📷 Time-lapse capture using a Raspberry Pi Camera  
- 🌐 **Local web server** for real-time data access  
- 🍃 Optimized for growing **basil** indoors  

## 🛠 Hardware

- Raspberry Pi Zero W  
- Capacitive soil moisture sensor  
- BH1750 or LDR light sensor  
- Peristaltic pump (5V/12V) with MOSFET or relay module  
- LED grow light  
- Raspberry Pi Camera  
- Power supply (5V 2.5A+ recommended)  
- Tubing and water reservoir  
- Wires, breadboard or custom PCB  

## 🌿 Plant

This greenhouse is tuned for **basil**, a fast-growing, light-loving herb ideal for indoor cultivation and timelapse photography.

## 🧠 Software Overview

Note: All code is written manually as part of the learning process – this repo focuses on the architecture and hardware setup.

- Sensor readings handled via GPIO  
- Data served through a lightweight Python web server (e.g., Flask)  
- Camera captures images at intervals  
- Option to save sensor logs in JSON or CSV  
- Final timelapse created by compiling photos into a video  

## 📷 Time-lapse

The system captures one photo every few minutes. After several days, the photos can be combined to visualize the plant’s growth over time.

## 🏠 Enclosure

- Built using acrylic or a plastic container  
- Mounted camera (top view or side)  
- LED light positioned directly above basil  
- Pump and reservoir hidden below or behind  

## 🔐 Remote Access

Access your greenhouse stats from any device on your network by connecting to the Raspberry Pi Zero’s IP. Future plans may include:

- External access via port forwarding or ZeroTier  
- Mobile-friendly web UI  
- Sensor graphing with Chart.js or similar  

## 📦 Future Ideas

- Web control panel to manually trigger watering or lighting  
- Telegram bot integration  
- Data logging to cloud services like Google Sheets or InfluxDB  
- Auto camera focus or tracking  
- Wi-Fi reconnect fallback and alert system  

## 🧪 Project Goals

- Learn electronics and GPIO control on the Pi  
- Practice Python and web development  
- Create a functional and useful IoT system  
- Grow healthy basil 🌿 indoors year-round  

## 📜 License

MIT License – feel free to remix, expand, or build your own version.

---

Made with 💧, 🌞 and 💚 by [YourGitHubUsername]
