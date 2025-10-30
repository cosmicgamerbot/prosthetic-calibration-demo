# Prosthetic Calibration Demo

## Overview

This is a **dummy proof-of-concept** for an intelligent prosthetic limb calibration system. This project is a non-functional simulation designed to demonstrate the architecture and key components of an AI-powered prosthetic calibration system.

## Purpose

The goal is to showcase how an intelligent calibration system could work for prosthetic limbs that continuously adapts to the unique gait and motion patterns of users. This demo provides a visual and interactive framework without actual sensor integration or machine learning functionality.

## Key Components

### 1. **Stickman Simulation with Inverse Kinematics**
- Visual representation of prosthetic limb movement
- Controllable stickman character demonstrating gait patterns
- Inverse kinematics for realistic joint movement simulation
- Interactive controls for adjusting limb parameters

### 2. **FastAPI Backend**
- RESTful API for data flow between components
- Endpoints for simulation control and parameter adjustment
- Mock AI calibration logic

### 3. **MQTT Mock Sensor Stream**
- Simulated sensor data generation
- Mimics real-time data from pressure sensors, gyroscopes, and accelerometers
- Publishes dummy telemetry data (torque, resistance, balance metrics)

### 4. **React Dashboard**
- Real-time visualization of gait and posture data
- Interactive graphs showing simulated sensor readings
- Manual fine-tuning controls for therapists
- Performance metrics display (comfort, stability, energy expenditure)

### 5. **Local SQLite Logging**
- Stores simulated session data
- Logs dummy calibration adjustments and parameters
- Provides historical data for visualization

## Technical Stack

- **TensorFlow Lite**: For simulated on-device learning (placeholder)
- **MQTT**: Mock sensor data communication protocol
- **FastAPI**: Python backend framework
- **React**: Frontend visualization dashboard
- **SQLite**: Local data logging and storage

## Important Note

⚠️ **This is a non-functional demonstration only.** No actual sensor integration, machine learning, or prosthetic control is implemented. This project serves as a visual and architectural prototype for educational and presentation purposes.

## Use Case Simulation

The system simulates:
- Real-time adaptive control adjustments
- Gait pattern analysis visualization
- Predictive maintenance alerts (dummy notifications)
- Offline operation suitable for rural rehabilitation centers
- Therapist dashboard for monitoring and manual adjustments

## Getting Started

(Implementation instructions would go here once the demo components are developed)

## License

This is a demonstration project for educational purposes.
