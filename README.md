# TINKERING LAB PROJECT

This project aims to design an Indoor Air Quality Monitoring System with the following primary features:</br>

<li>Utilizing MQ sensors and DTH11 to detect air parameters, temperature, and humidity.</br>
<li>Recording values in an Excel sheet, accessible remotely via OneDrive.</br>
<li>Integrating ESP32's Wi-Fi capabilities to enable mobile connectivity and send instant alerts based on sensor readings.

# Sensors

## MQ Sensors

<li> MQ2 : Detects smoke concentration, LPG, butane, propane, methane, alcohol, smoke, and hydrogen.
<li> MQ4 : Senses the amount of methane or natural concentration gas
<li> MQ7 : Specially for CO (Carbon Monoxide)
<li> MQ135 : Detects a broad range of gases, including ammonia (NH3), benzene, alcohol, and carbon dioxide (CO2).

## DHT11 Sensor
<li> Measures temperature and humidity


# For Messaging

For the SMS part we used Twilio, It is a cloud-based communication platform  provides a set of APIs for 
the integration of SMS from ESP 32 to Smart phone and is used in our 
project for the same. </br>
Under abnormal conditions, the ESP32 connects to the internet via WiFi 
and sends out a SMS to the registered number on Twilio.

# How to Run

- To run, one must install Arduuino IDE and select the ESP32 board  and run this code.
- The setup will start showing values and if any harmful gas is detected, a red LED glows and a SMS is sent
- We can also monitor the trends of the air quality on an Excel Sheet using Arduino UNO.


# EXPERIMENT
https://github.com/aksahil2205/Indoor-Air-Quality-Monitor/assets/120297640/3c705a95-3218-4254-829a-77d265b3d1b6




# APPLICATIONS IN INDUSTRIES
 - Industrial Safety Monitoring
 - Smart Agriculture using air quality monitoring
 - Environmental monitoring
 - Research and Education
 - Smart Cities
 - Greenhouse monitoring
 - Can be used in sensitive chambers such as nuclear power plant, submarines etc. for safety enhancement

## Team Members

- Patel Ayush (2022CSB1101)
- Pranav Menon (2022CSB1329)
- Hartik Arora (2022CSB1314)
- Jyoti (2022CSB1319)
- Aniket Kumar Sahil (2022CSB1067)
