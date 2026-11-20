 Smart IoT-Based Room Monitoring and Automation System

Project Overview
The Smart Room Monitoring and Automation System is an IoT-based project developed using ESP32, Embedded C/C++, and Blynk IoT. It monitors room temperature, humidity, light intensity, and human movement using sensors and provides real-time monitoring and automation.

Features
- Real-time temperature and humidity monitoring.
- Automatic light control based on room brightness and motion.
- Human motion detection using PIR sensor.
- Remote monitoring through Blynk IoT dashboard.
- Manual and automatic output control.
- Wi-Fi-based communication using ESP32.

Technologies Used
- Programming: Embedded C/C++
- Microcontroller: ESP32
- IDE: Arduino IDE
- IoT Platform: Blynk IoT
- Circuit Design: Tinkercad, Fritzing

 Hardware Components
- ESP32 Development Board
- DHT11 Temperature and Humidity Sensor
- PIR Motion Sensor
- LDR Sensor
- 10kΩ Resistor
- Relay Module
- Breadboard
- Jumper Wires

 Working Principle
1. DHT11 collects temperature and humidity data.
2. LDR measures the surrounding light intensity.
3. PIR sensor detects human movement.
4. ESP32 processes the sensor readings.
5. In automatic mode, the output turns ON when movement is detected in a dark room.
6. Blynk IoT displays sensor readings and allows remote control.

Applications
- Smart home automation
- Room monitoring systems
- Energy-efficient lighting
- IoT-based security and monitoring
- Smart classrooms and offices

 Future Improvements
- Add mobile notifications for motion detection.
- Integrate additional environmental sensors.
- Add energy consumption monitoring.
- Develop a more advanced automation dashboard.

 Project Structure
```text
Smart-IoT-Room-Automation-System/
│
├── README.md
├── LICENSE
├── .gitignore
│
├── src/
│   └── SmartRoomAutomation.ino
│
└── docs/
    ├── WIRING.md
    └── BLYNK_SETUP.md
```

Getting Started
1. Install Arduino IDE.
2. Install the ESP32 board package.
3. Install the required Blynk and DHT libraries.
4. Configure your Wi-Fi and Blynk credentials in the Arduino sketch.
5. Connect the sensors according to the wiring instructions.
6. Upload the code to ESP32.
7. Monitor the readings through the Blynk dashboard.



