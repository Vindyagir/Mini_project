# Mini_project
# Human Safety Tracking Device

## Project Overview
The **Human Safety Tracking Device** is an IoT-based wearable safety solution designed to protect vulnerable individuals, including women, children, and the elderly, by providing real-time location tracking and emergency alerts. The device leverages GPS and GSM modules to pinpoint the user’s location and send immediate notifications to designated emergency contacts.

## Features
- **Real-time Location Tracking**: Utilizes GPS to provide accurate location data.
- **Emergency Alert System**: Sends instant SMS and calls to pre-configured contacts in distress situations.
- **Compact Wearable Design**: Designed for ease of use and comfort.
- **Two-Way Communication**: Facilitates interaction between the user and emergency responders.
- **Battery Backup**: Equipped with a rechargeable Li-ion battery for continuous operation.
- **Integration with Smart Devices**: Potential for future upgrades including AI-based threat detection and health monitoring.

## Components Used
- **Microcontroller**: Arduino Nano
- **GPS Module**: Used for real-time tracking
- **GSM Module (SIM800L)**: Sends emergency alerts via SMS and calls
- **Push Buttons**: Triggers emergency alerts
- **Resistors (10K ohm)**: Used for circuit stabilization
- **Li-ion Battery**: Provides power supply
- **Battery Charging Module**: Ensures continuous power supply
- **Slide Toggle Switch**: Controls power operations

## Circuit Diagram
The circuit integrates an Arduino Nano microcontroller that connects to the GPS and GSM modules. Upon activation of the emergency button, the GPS module captures the location data, which is then transmitted via the GSM module to emergency contacts.
![Screenshot 2025-01-01 214012](https://github.com/user-attachments/assets/12621059-32d5-46d7-8c65-a4f6e470cc55)

## How It Works
1. The device remains in standby mode, continuously acquiring GPS location data.
2. When the user presses the emergency button:
   - The GPS module captures the location.
   - The GSM module sends an SMS with location details to pre-configured contacts.
   - An emergency call is placed to a designated contact for immediate response.
3. The system remains active until manually reset.

## Applications
- **Personal Safety**: Ideal for women, children, and elderly individuals.
- **Emergency Response**: Useful for lone workers and travelers.
- **Law Enforcement**: Can assist in tracking and responding to critical situations.
- **Healthcare**: Integration with health sensors for medical emergencies.

## Advantages
- Provides **real-time monitoring** for enhanced safety.
- Ensures **quick emergency response** through instant alerts.
- Compact and lightweight design for easy carrying.
- Cost-effective solution using readily available components.
- Can be enhanced with additional features like fall detection and AI-based threat analysis.

## Future Scope
- **AI-Based Threat Prediction**: Implementing machine learning for predictive safety.
- **Integration with Smart Devices**: Connectivity with home automation and security systems.
- **Wearable Design Enhancement**: Improved comfort and user experience.
- **Health Monitoring**: Addition of biometric sensors for tracking vital signs.

## Installation & Setup
### Prerequisites
- Arduino IDE installed on your system.
- Required libraries for GPS and GSM communication.
- A working SIM card for the GSM module.

### Steps to Upload Code
1. Connect the **Arduino Nano** to your PC via USB.
2. Open the Arduino IDE and load the provided code.
3. Install necessary libraries (`SoftwareSerial`, `TinyGPS++`, etc.).
4. Select the correct COM port and board type.
5. Upload the code and monitor the serial output for troubleshooting.
### Working vedio
- https://drive.google.com/file/d/1LPJYerHBfEf-voRuemwthOm6DadEgsYf/view?usp=drive_link
### Guide
- **Keerthy N**, Assistant Professor, Department of ECE, Global Academy of Technology

## License
This project is open-source and available under the MIT License.

---
For more details, refer to the full project report.

