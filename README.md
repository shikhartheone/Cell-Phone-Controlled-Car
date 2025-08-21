# Cell Phone Controlled Car 🚗📱

A bot controlled via a smartphone’s accelerometer using Wi-Fi communication.  
The project uses **NodeMCU ESP8266** as the microcontroller and an **L298N motor driver** to control the motors.  
The Android app sends accelerometer data (X, Y, Z axes) over Wi-Fi, which is received by the NodeMCU and used to navigate the car in real time.  

## Features
- Smartphone accelerometer-based control (tilt to move: forward, backward, left, right).  
- NodeMCU ESP8266 for Wi-Fi communication.  
- L298N motor driver for driving DC motors with sufficient current.  
- Voltage regulation for stable 5V supply.    

## Tech Stack
- NodeMCU ESP8266 (IoT microcontroller)  
- L298N Motor Driver  
- Android App (Accelerometer-based)  
- Arduino IDE  
