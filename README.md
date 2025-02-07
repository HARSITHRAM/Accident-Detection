# **Anti-Theft and Vehicle Accident Alert System**  

## **Overview**  

The **Anti-Theft and Vehicle Accident Alert System** is a smart security solution that uses **Arduino Uno**, **GPS**, **GSM**, and an **accelerometer** to detect unauthorized vehicle movement or accidents. The system instantly alerts the owner via **SMS and phone calls**, sharing real-time location data. Additionally, users can remotely request the vehicle’s location using a simple SMS command. This project aims to enhance vehicle safety and security with minimal hardware.  

## **Features**  

- **Real-Time Tracking**: Uses GPS to provide accurate location updates.  
- **Accident Detection**: Detects collisions via an accelerometer and sends immediate alerts.  
- **Anti-Theft Protection**: Notifies the owner of unauthorized vehicle movement.  
- **Remote Location Request**: Users can retrieve their vehicle's location via SMS.  
- **GSM-Based Alerts**: Sends SMS notifications and calls in case of theft or accidents.  

## **Components Used**  

| Component                      | Quantity |  
| ------------------------------ | -------- |  
| Arduino Uno                    | 1        |  
| GPS Module (NEO-6M)            | 1        |  
| GSM Module (SIM800L)           | 1        |  
| Accelerometer (ADXL335)        | 1        |  
| Lithium-Ion Battery            | 1        |  
| Miscellaneous (Wires, PCB, etc.) | Various  |  

## **Circuit Connections**  

- **Arduino Uno**: Controls all components and processes data.  
- **GPS Module**: Provides real-time vehicle location.  
- **GSM Module**: Sends alerts via SMS and calls.  
- **Accelerometer**: Detects movement and accidents.  
- **Power Supply**: Battery powers the entire system.  

## **Installation & Setup**  

1. Clone this repository:  
   ```sh  
   git clone https://github.com/HARSITHRAM/anti-theft-alert-system.git  
   ```  
2. Install the **Arduino IDE** and required libraries:  
   - TinyGPS++.h  
   - SoftwareSerial.h  
3. Upload the Arduino code to the **Arduino Uno** board.  
4. Insert a SIM card into the **GSM Module (SIM800L)**.  
5. Power on the system and test location tracking and alerts.  

## **How It Works**  

1. If the vehicle experiences unauthorized movement, the system alerts the owner.  
2. In case of an accident, the system detects sudden motion changes using the accelerometer and sends an emergency alert.  
3. The user can request the vehicle's location by sending an SMS command.  
4. The system continuously updates and reports vehicle status via **GSM** communication.  

## **Applications**  

- **Vehicle Security**: Prevents theft by providing real-time alerts.  
- **Emergency Response**: Alerts emergency contacts in case of accidents.  
- **Fleet Management**: Helps monitor vehicle locations for businesses.  

## **Future Enhancements**  

- **Mobile App Integration**: Developing an app for enhanced control and monitoring.  
- **AI-Based Motion Detection**: Improving accuracy in theft and accident detection.  
- **Wi-Fi & IoT Expansion**: Using ESP8266/ESP32 for cloud-based tracking.  

## **Contributing**  

Contributions are welcome! Fork the repository and submit pull requests for improvements.  

## **Contact**  

For queries or collaborations, reach out:  

- **GitHub**: [@HARSITHRAM](https://github.com/HARSITHRAM)  
- **Email**: [harsithram08@gmail.com](mailto:harsithram08@gmail.com)  

