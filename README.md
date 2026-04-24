# 🚗 Gesture-Driven Smart Robotic Vehicle Using IoT

## 📌 Abstract
Gesture-controlled robotic systems represent an intuitive and efficient way of human–machine interaction. This project presents the design and implementation of a DIY Gesture Controlled Robot Car using two ESP8266 microcontroller modules, enabling wireless control through simple hand movements.

The system eliminates the need for complex communication hardware such as NRF24 modules or advanced WiFi network configurations, making it highly suitable for beginners and students. One ESP8266 unit acts as a gesture transmitter, interfaced with motion sensors to detect hand movements, while the second ESP8266 functions as a receiver mounted on the robot car.

The detected gestures are wirelessly transmitted using direct ESP-to-ESP communication, allowing real-time control of the robot’s movement such as forward, backward, left, and right directions.

This project provides a low-cost, efficient, and easy-to-implement solution for gesture-based robotic control and serves as a foundation for advanced IoT and robotics applications.

---

## 👨‍💻 Project Members
1. **SHAIKH ARSHI FATMA ASLAM** (Team Leader)  
2. CP MOHAMMED BAKAR MOHAMMED JAFFER  
3. KHAN ALISHA RAZZAK  
4. MULLA IZHAR ASHRAF ISHTIYAQUE  

---

## 👨‍🏫 Project Guide
- **PROF. MOHAMMED JUNED** (Primary Guide)

---

## ⚙️ Deployment Steps

### 🔹 Step 1: Install Software
- Install **Arduino IDE**
- Add ESP8266 board via Board Manager

### 🔹 Step 2: Setup Hardware
- Connect **MPU6050 sensor** to Transmitter ESP8266  
  - SDA → D2  
  - SCL → D1  
- Connect **L298N Motor Driver** to Receiver ESP8266  
- Connect motors and power supply

### 🔹 Step 3: Upload Code
- Upload **Transmitter code** to one ESP8266  
- Upload **Receiver code** to another ESP8266  

### 🔹 Step 4: Configure WiFi
- Receiver ESP8266 creates hotspot:
  - SSID: `ESP_CAR`
  - Password: `12345678`
- Transmitter connects to this hotspot

### 🔹 Step 5: Run the System
- Power ON both ESP8266 modules  
- Tilt your hand → Car moves accordingly 🚗  

---

## 🛠️ Platform, Libraries and Tools Used

### 🔹 Hardware
- ESP8266 (NodeMCU) × 2  
- MPU6050 Accelerometer & Gyroscope  
- L298N Motor Driver  
- DC Motors & Robot Chassis  

### 🔹 Software
- Arduino IDE  
- Embedded C (Arduino Programming)

### 🔹 Libraries
- `ESP8266WiFi.h`  
- `Wire.h`  
- `MPU6050.h`  

---

## 📊 Applications
- Assistive technology for disabled users  
- Smart robotics projects  
- Industrial automation  
- Remote-controlled systems  

---

## 🔮 Future Scope
- Add camera for live streaming  
- Improve gesture accuracy using AI/ML  
- Mobile app integration  
- Voice-controlled system  

---

## 📚 References
- Bahga, A., & Madisetti, V. (2015). *Internet of Things: A Hands-On Approach*.  
- Kolban, N. (2016). *Kolban’s Book on ESP8266*.  
- Kumar, S., & Sharma, P. (2021). *Gesture Controlled Robotic Vehicle Using IoT*, IJERT.  
- Singh, R., et al. (2020). *Hand Gesture Controlled Robot Using Accelerometer*, IEEE.  

---

## 🙏 Acknowledgement
We would like to thank our project guide **Prof. Mohammed Juned** for his valuable guidance and support. We also express our gratitude to our institution, faculty members, and teammates for their encouragement throughout the project.
