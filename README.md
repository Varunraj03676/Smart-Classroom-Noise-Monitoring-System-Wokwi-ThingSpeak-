# Smart Classroom Noise Monitoring System

ESP32 IoT Project that monitors classroom noise levels using a potentiometer (simulated sensor) and uploads the data to ThingSpeak in real-time. The system can also provide a visual alert via an LED when the noise exceeds a defined threshold, making it ideal for smart classroom monitoring or IoT learning projects.

## Overview

Classroom noise monitoring is important for maintaining an effective learning environment. This project uses an ESP32 microcontroller to simulate real-time noise measurement:

- Noise is simulated using a potentiometer in Wokwi or a real sensor in hardware.
- Data is uploaded to ThingSpeak, an IoT cloud platform, where it can be visualized in real-time.
- Optional LED alerts notify when noise levels exceed a certain threshold.
- The project works in simulation (Wokwi) and on real ESP32 hardware, making it easy to test before deploying physically.

## Features

- Simulate classroom noise with a potentiometer
- Upload noise data to ThingSpeak for real-time monitoring
- high noise levels (configurable threshold)
- Easy to customize for different sensors or IoT applications
- Works in Wokwi simulation or on real ESP32 boards

## Requirements

- ESP32 development board
- Arduino IDE (with ESP32 board manager installed)
- WiFi connection or mobile hotspot
- ThingSpeak account (for cloud data visualization)
- Wokwi simulator (optional, for simulation without hardware)


    digitalWrite(LED_BUILTIN, LOW);
}
