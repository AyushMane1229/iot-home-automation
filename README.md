# iot-home-automation
# 🏠 Home Automation IoT Project  
*Internship Project @ Emertxe*

A complete IoT-based home automation system built during my internship at Emertxe. This project uses hardware sensors, simulation via PicSimLab, and the Blynk mobile app for remote control and monitoring.

---

## 🚀 Project Features

- **Garden Lights Automation**  
  Automates LED brightness using an LDR sensor and PWM based on ambient light levels.

- **Temperature Monitoring & Control**  
  Reads temperature via an LM35 sensor. Automatically toggles heater or cooler via relays. Displays live readings on CLCD and Blynk with alerts when thresholds (e.g., 35 °C) are crossed.

- **Water Tank Valve Control**  
  Monitors water tank level via serial communication. Automatically controls inlet/outlet valves based on level thresholds (e.g., maintain above 2000 L) with full manual override and push-button control via Blynk.

---

## 📦 Components & Tools

- **Hardware**  
  - Arduino Uno (or PIC/ESP)  
  - LDR light sensor  
  - LM35 temperature sensor  
  - Relay modules (heater, cooler, valves)  
  - LEDs, valves, CLCD display  

- **Software & Tools**  
  - Arduino IDE – for firmware  
  - PicSimLab – for simulation (.pzw files)  
  - Blynk IoT App – for dashboard/control  
  - Serial interface – for water tank level readings  

---

## 🖼️ Screenshots

![Screenshot of the project](git clone https://github.com/AyushMane1229/LAZAREV.git)  


## 🛠️ Installation

To run this project locally, follow these steps:

1. Install required tools

    - Install Arduino IDE

    - Download and install PicSimLab

    - Install the Blynk app on your phone and copy the Auth Token

2. Run the Simulation

    - Open simulation/home_automation.pzw in PicSimLab

    - Connect virtual sensors, relays, LEDs, valves, and serial module accordingly

3. Upload Firmware

    - Open firmware/HomeAutomation.ino in Arduino IDE

    - Add your Blynk Auth Token

    - Upload the code to your Arduino Uno

4. Operate the System

    - Start simulation in PicSimLab

    - Launch Blynk on your phone

    - Control garden lights, heater/cooler, and tank valves from the mobile dashboard


🤝 Contributions

 Contributions to the Home Automation IoT Project are welcome! To contribute, follow these steps:

   1. Fork the repository.

   2. Create a new branch (git checkout -b feature/your-feature).

   3. Make your changes and commit them (git commit -am 'Add new feature').

   4. Push to the branch (git push origin feature/your-feature).

   5. Create a new Pull Request
      


