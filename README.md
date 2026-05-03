# Farm-Monitoring-system-on-wokwi
Overview

This project is a smart agriculture monitoring system built using the ESP32-S3. It enables real-time tracking of environmental conditions and cloud-based data logging for efficient and data-driven farming.

The system is designed with a scalable architecture that supports remote monitoring, edge processing, and future automation such as smart irrigation and TinyML integration.

Features
Temperature monitoring
Humidity tracking
Soil moisture detection
Light intensity measurement
Soil pH monitoring
Real-time data transmission
Sensor data is sent to ThingSpeak every 20 seconds using Wi-Fi
Cloud data logging
Enables storage and visualization of historical data
Edge computing
Local data acquisition and preprocessing on ESP32-S3
Simulation support
Developed and tested using the Wokwi simulator
System Architecture

Sensors → ESP32-S3 → Wi-Fi (HTTP) → ThingSpeak Cloud → Data Visualization
