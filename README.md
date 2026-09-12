# AquaTrace

### Smart Water Pipeline Leak Detection & Localization System

AquaTrace is a simulation-based prototype for monitoring water pipelines and detecting possible leaks by analyzing flow and pressure conditions at different points in the pipeline.

The project focuses on identifying abnormal readings and estimating the pipeline section where a leak may have occurred.

## Features

- Flow and pressure monitoring
- Multiple monitoring nodes
- Leak-zone identification
- Baseline calibration
- Adaptive threshold-based detection
- Real-time telemetry
- Event logging
- Leak confidence estimation
- 3D pipeline visualization
- Laptop and mobile dashboards
- ESP32 / ESP-NOW communication concept

## How It Works

The pipeline is divided into multiple monitoring sections. Each node provides simulated flow and pressure readings.

The system compares these readings with the normal calibrated conditions. When the readings show an abnormal pattern, the system analyzes the affected section and estimates the probable location of the leak.

The dashboard displays the pipeline status, sensor readings, detected zone, confidence level, and event history.

## Project Structure

```text
AquaTrace/
│
├── laptop.html
├── mobile.html
├── laptop-dashboard.png
├── mobile-dashboard.png
├── leak-detection.png
└── README.md
