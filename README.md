# WiFi-Controlled Home Automation using Blynk IoT

This project demonstrates a basic home automation system using WiFi and the Blynk IoT platform. It allows users to control home appliances remotely using a smartphone.

## 🔧 Project Description

The goal of this project is to automate common household devices (such as lights and fans) using NodeMCU (ESP8266) and control them via the Blynk mobile app over WiFi.

## 📱 Features

- Remotely control home appliances using a smartphone
- Real-time device status monitoring
- WiFi-based connectivity using ESP8266 NodeMCU
- Easy-to-use Blynk IoT app interface

## 🧰 Components Used

- NodeMCU ESP8266
- Relay Module (2-channel or more)
- AC Bulb (as load)
- Power Supply
- Jumper Wires
- Blynk IoT App (Android/iOS)

## 📲 Blynk Setup

1. Download the **Blynk IoT** app from Play Store or App Store.
2. Create a new project and select **ESP8266** as the device.
3. Add buttons for each appliance and assign digital pins (e.g., D1, D2).
4. Copy the Auth Token from the app.

## 🧪 How It Works

- The NodeMCU connects to WiFi and listens for commands via the Blynk app.
- When a button is pressed in the app, the corresponding GPIO pin is toggled.
- This action switches the relay on/off, thereby controlling the appliance.

## 💻 Code Overview

The code connects the NodeMCU to WiFi and Blynk, and defines virtual pins or digital outputs to control relays.

> Note: You need to insert your own **WiFi SSID**, **Password**, and **Blynk Auth Token** in the code.

## 📂 Files Included

- Source Code (.ino file)
- Circuit Diagram
- Project Documentation (PDF)

## 🔌 Circuit Diagram

- **D1 → IN1 of Relay** (Appliance 1)
- **D2 → IN2 of Relay** (Appliance 2)
- **Relay → AC Appliances**

Ensure the relay is connected to a proper AC supply and the NodeMCU is powered via USB or a stable 5V source.

## 📸 Screenshots

(Add screenshots of your hardware setup and Blynk app interface here.)

## 🚀 Future Enhancements

- Add sensors (temperature, motion, etc.)
- Voice control with Google Assistant
- Scheduling features
- Energy monitoring

## 📜 License

This project is open-source and available for modification and use under the [MIT License](LICENSE).

---

Feel free to clone, modify, and build upon this project!

