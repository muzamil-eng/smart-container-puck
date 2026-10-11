# Smart Container Base Puck

Embedded IoT status-monitoring module built on the Seeed Studio XIAO ESP32-C3 platform, integrating load cell, thermistor, and accelerometer telemetry for real-time container tracking.

## Project Overview
The **Smart Container Base Puck** leverages a high-performance microcontroller architecture to collect real-time sensor data, process diagnostic thresholds, and trigger instant visual status feedback. Designed with a modular approach, the system validates multi-sensor logic for applications in smart storage and logistics monitoring.

## Hardware & Tech Stack
* **Microcontroller:** Seeed Studio XIAO ESP32-C3
* **Sensors Integrated:**
  * **Load Cell & Strain Gauge:** Tracks weight variance and payload presence.
  * **NTC Thermistor:** Monitors ambient temperature thresholds.
  * **MPU6050 Accelerometer / Gyroscope:** Detects tilt, orientation changes, and motion.
* **Firmware:** C / C++ (Arduino Framework)
* **Simulation & Circuit Validation:** Tinkercad / Breadboard Prototyping
* **Visual Telemetry:** Dynamic RGB LED status indicators

## Key Features & Logic
* **Multi-Sensor Telemetry:** Simultaneous sampling of weight, thermal conditions, and spatial orientation.
* **Control Loop Firmware:** C++ firmware executing threshold logic for real-time state detection.
* **Visual Alerts:** Dynamic RGB LED indicator patterns triggered by weight shifts, thermal warnings, or tipping events.
* **API & Workflow Integration:** Optimized firmware debugging and sensor calibration using AI-assisted analysis pipelines.
## 📋 Project Management & Engineering Documentation
* **Work Breakdown Structure (WBS) & Timeline:** Managed project execution across a structured multi-week milestone schedule.
* **Bill of Materials (BOM) & Procurement:** Cataloged component specs, pin compatibility, power budgets, and procurement tracking.
* **Design Sketches & Schematics:** Hand-drafted orthographic concepts and Tinkercad breadboard schematics prior to physical assembly.
