# 🌤️ Wokwi: MicroPython Weather Station with MQTT

This project runs on the [Wokwi](https://wokwi.com) simulator and demonstrates how to use a **DHT22 sensor** with an **ESP32** board to measure temperature and humidity, then publish the data to an MQTT broker.

---

## 🔗 Live Simulation

👉 [Run on Wokwi](https://wokwi.com/projects/) *(Replace with your project link)*

---

## 🧰 Components Used

- ESP32 Dev Board (simulated)
- DHT22 Temperature & Humidity Sensor
- WiFi (Wokwi-GUEST simulated network)
- MQTT Broker: `broker.mqttdashboard.com`

---

## 🛠️ Features

- Reads temperature and humidity via DHT22
- Connects to Wokwi-GUEST WiFi
- Sends JSON-formatted data to MQTT topic: `wokwi-weather`
- Only publishes data if there's a change

---


