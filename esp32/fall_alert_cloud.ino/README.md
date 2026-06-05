# ESP32 Firmware

Firmware responsible for collecting sensor data, performing fall detection inference, and communicating with cloud services.

## Hardware Components

* ESP32
* MPU6050
* GPS Module

## Responsibilities

* Read sensor values
* Detect falls
* Collect GPS coordinates
* Send alerts to backend
* Upload sensor data

## Required Libraries

* WiFi.h
* Wire.h
* MPU6050.h
* TinyGPSPlus.h
* HTTPClient.h

## Upload Instructions

1. Open Arduino IDE
2. Install ESP32 Board Package
3. Install required libraries
4. Connect ESP32
5. Upload firmware
