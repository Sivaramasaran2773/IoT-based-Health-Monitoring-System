# IoT-based-Health-Monitoring-System
This project enables the monitoring of a patient's health, including heart rate (BPM) and body temperature, by utilizing the ESP8266-01 WiFi module. The monitored data is sent to a ThingSpeak Server, where it is stored in your own specific Channel. Additionally, the system is integrated with IFTTT applets using ThingHTTP and React, facilitating the simultaneous update of the monitored data to Google Sheets. In case of any abnormal behavior detected, the system automatically sends a panic alert to your email. 

**The primary motivation behind this project is to enable remote monitoring of your parents or loved ones from anywhere in the world. By doing so, you can take prompt action if any health issues arise and ensure timely assistance, potentially preventing any delays in providing necessary care.**

### Hardware Components
* Arduino UNO Board
* ESP8266-01 Module
* LCD Display
* Pulse Sensor
* DS18B20 Temperature Sensor
* DC Buzzer
* Potentiometer-10k pot
* 4.7K&100 ohm Resistor

### Block Diagram
![image](https://github.com/Sivaramasaran2773/IoT-based-Health-Monitoring-System/assets/96780921/eccd212c-a4f9-423f-adb2-babc68e08336)

### Key Steps
1. Assembling the sensors with the Arduino Board
2. Creating a ThingSpeak Server and Configuring ESP8266-01
3. Coding and Uploading to the Arduino UNO and Transmitting data to ThingSpeak Server.
4. Creating IFTTT Applets and Integrating with ThingSpeak Server

### Prototype
![image](https://github.com/Sivaramasaran2773/IoT-based-Health-Monitoring-System/assets/96780921/132d1c21-97ea-4b24-8c45-2ecd87e79045)

### Circuit diagram for configuring ESP8266-01 Module:
*This configuration pairs your ESP8266-01 Module with your Wifi or Personal Hotsot Network and connects with your respective ThingSpeak channel.*

![image](https://github.com/Sivaramasaran2773/IoT-based-Health-Monitoring-System/assets/96780921/4ae2b52c-8213-42d3-9c27-a847561ba50a)

### Circuit diagram of IoT based patient health monitoring system:
*Use breadboard for hassel free connections*

![image](https://github.com/Sivaramasaran2773/IoT-based-Health-Monitoring-System/assets/96780921/2f50f3ac-5eb9-43bd-afaf-586879a551cb)


## My ThingSpeak Channel
https://thingspeak.com/channels/2184350

![image](https://github.com/Sivaramasaran2773/IoT-based-Health-Monitoring-System/assets/96780921/7af062de-b062-4ae6-a33e-68c382c920ad)

## My Google Sheet
https://docs.google.com/spreadsheets/d/1pZmrKEq9TK33q_4hTG9QoLMB3TxziMNtdptwzvpydN8/edit?pli=1#gid=0

![image](https://github.com/Sivaramasaran2773/IoT-based-Health-Monitoring-System/assets/96780921/37e2dda8-b977-4006-a633-f4b6e2ce277a)

## Panic Email:

![image](https://github.com/Sivaramasaran2773/IoT-based-Health-Monitoring-System/assets/96780921/61a4ff62-f7b1-4578-84de-6f1eb8767711)

