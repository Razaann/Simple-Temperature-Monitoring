# 🌡️ ESP32 Temperature Monitoring with DHT22 & LED Indicators  

This project is a simple temperature monitoring system using an **ESP32** and a **DHT22** temperature & humidity sensor, created in **Wokwi**. The temperature readings are displayed on the **Serial Monitor**, and an LED system provides a quick visual indication of the temperature range.  

## 🚀 Features  

✅ **Real-time Temperature Monitoring** – Reads temperature from the DHT22 sensor and prints it to the Serial Monitor.  
✅ **LED Temperature Indicator** – Three LEDs indicate different temperature ranges:  

- 🔵 **Blue LED** → Cold  
- 🟢 **Green LED** → Room Temperature  
- 🔴 **Red LED** → Hot  

✅ **Wokwi Simulation** – Fully simulated on [Wokwi](https://wokwi.com/), making it easy to test without hardware.  

## 🔧 How It Works  

1. The **ESP32** reads temperature data from the **DHT22 sensor**.  
2. The **temperature is printed** on the **Serial Monitor**.  
3. Depending on the temperature:  
   - If it's **cold**, the **blue LED** lights up.  
   - If it's **room temperature**, the **green LED** lights up.  
   - If it's **hot**, the **red LED** lights up.  
