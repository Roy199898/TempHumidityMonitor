# TempHumidityMonitor
# Temperature & Humidity Monitoring System

This project is a basic embedded system designed to read temperature and humidity using the **DHT11 sensor** and display the data on an **OLED screen (128x64, I2C SSD1306)** using an **Arduino UNO**.

---

## ✅ Features

- Reads temperature and humidity from a DHT11 sensor.
- Displays the data on a 0.96" I2C OLED display.
- Prints data to the Serial Monitor.
- Simple and beginner-friendly design.
- Simulatable using Proteus or testable on real hardware.

---

## 🛠️ Hardware Used

| Component      | Specification                        |
|----------------|--------------------------------------|
| Microcontroller| Arduino UNO                          |
| Sensor         | DHT11 (Temperature & Humidity)       |
| Display        | OLED 128x64, I2C (SSD1306)           |
| Others         | Jumper Wires, Breadboard (if needed) |

---

## 🔌 Pin Connections

| Component | Arduino Pin |
|-----------|-------------|
| DHT11 VCC | 5V          |
| DHT11 GND | GND         |
| DHT11 DATA| D8          |
| OLED SDA  | A4          |
| OLED SCL  | A5          |

---

## 💻 Required Libraries

Install the following libraries via Arduino Library Manager:

- **Adafruit Unified Sensor**
- **DHT sensor library by Adafruit**
- **Adafruit SSD1306**
- **Adafruit GFX Library**

---

## 📜 How It Works

1. The Arduino reads data from the DHT11 sensor.
2. Temperature (°C) and Humidity (%) values are printed to the Serial Monitor.
3. The OLED display shows both temperature and humidity values in real-time.

---

## 🔁 Sample Output (OLED Display)


