# 📡 IoT-Based Real-Time Weather Monitoring and Reporting System

**Ever dreamed of creating your own weather station? This project makes it real!**

We're blending the power of sensors, wireless communication, and real-time displays to give you a system that watches the skies — and reports back with precision.

**Imagine:**

* Knowing the temperature, humidity, air quality, and rain status from across your farm, campus, or backyard.
* Seeing live readings on a crisp LCD screen.
* Wirelessly transmitting data to a remote location — no internet needed!

This project turns everyday electronics into **a powerful environmental monitoring system.**

## 🔍 Here's a sneak peek of the final setup:
![](https://github.com/Mahak0204-svg/Weather-Station/blob/2402e6a65ae7b11e35fd83c6a2def67a346d74a1/Final%20Project%20Image)

## 🔥 Why This Weather Station is a Game Changer 🔥

**All-in-One Weather Insight:**

🌡️ Temperature & 💧 Humidity — via the trusty DHT11 sensor

🌫️ Air Quality — with the MQ-135 gas sensor

🌧️ Rain Detection — using a digital rain sensor

**Wireless Communication:**

* Long-range data transmission with the HC-12 module (up to 1 km!)

* Works in remote areas — no Wi-Fi or mobile data needed

**Instant LCD Feedback:**

* See all data on a compact 16x2 I2C LCD — no PC required

**Arduino-Powered Simplicity:**

* Built using Arduino Uno

* Coded in the Arduino IDE with beginner-friendly libraries

**Debug with Ease:**

* Data also logs to the Serial Monitor for analysis and testing

## 🔌 Let’s take a look at the circuit:
![](https://github.com/Mahak0204-svg/Weather-Station/blob/2402e6a65ae7b11e35fd83c6a2def67a346d74a1/Circuit%20Diagram)

## 🛠️ What You’ll Need
**Component	Description**
* Arduino Uno	Main controller
* DHT11	Temperature and humidity sensor
* MQ-135	Gas sensor for air quality
* Rain Sensor	Digital rain detection
* HC-12 Module	Long-range (up to 1 km) wireless communication
* 16x2 I2C LCD	Displays sensor data
* Power Adapter	Powers the whole system
* Breadboard & Wires	Connections

## 🎥 See it in Action
Want to see the system in real-time? Watch this demo video!

[▶️ Weather Station Demo](https://github.com/Mahak0204-svg/Weather-Station/blob/2402e6a65ae7b11e35fd83c6a2def67a346d74a1/Demo%20Video)

## 🧠 How It Works
* Sensors capture environmental data every 2 seconds.
* Arduino formats and displays this data on the LCD.
* Data is sent wirelessly using HC-12 to a paired receiver.
* Output is simultaneously logged to the Serial Monitor for debugging.

## 💻 Code Overview
* DHT.h: Reads temperature and humidity
* SoftwareSerial.h: Enables HC-12 communication on custom pins
* Wire.h & LiquidCrystal_I2C.h: Interface with LCD
* The sketch is modular for easy upgrades (e.g., cloud integration)

## 📊 Results Snapshot
Temperature (°C)	Humidity (%)	Air Quality	Rain Detected
35	36	70	Yes
39	36	72	Yes
38	35	50	Yes

# 📈 Future Scope
* Add Wi-Fi and upload data to the cloud ☁️
* Build a web dashboard or mobile app 📱
* Integrate solar power for remote independence 🔋
* Connect more sensors: barometric pressure, UV, wind 🌬️
