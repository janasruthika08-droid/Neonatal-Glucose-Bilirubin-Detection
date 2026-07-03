# Detection of Glucose and Bilirubin in Neonates Using Non-Invasive Optical Sensing

![Project Status](https://img.shields.io/badge/Status-Completed-success)
![Platform](https://img.shields.io/badge/Platform-ESP32-blue)
![Domain](https://img.shields.io/badge/Domain-Biomedical%20Engineering-green)

## Project Overview

Neonatal jaundice and hypoglycemia are among the most common medical conditions affecting newborns and require continuous monitoring for timely intervention. Conventional diagnostic techniques rely on invasive blood sampling, which can cause discomfort, increase infection risk, and limit the feasibility of frequent measurements.

This project presents a **portable, low-cost, and non-invasive optical sensing system** capable of estimating **bilirubin** and **glucose** concentrations in neonatal tissue using multi-wavelength spectroscopy and embedded signal processing.

The proposed system utilizes optical absorption characteristics of biological tissues, a silicon PIN photodiode for signal acquisition, and an ESP32 microcontroller for real-time processing and display of estimated biochemical parameters.

---

## Problem Statement

Current clinical methods for measuring neonatal bilirubin and glucose levels require invasive blood collection procedures.

Challenges include:

- Pain and discomfort for newborns
- Risk of infection
- Difficulty in frequent monitoring
- Limited accessibility in resource-constrained settings

The objective of this project is to develop a non-invasive alternative that enables continuous and real-time monitoring.

---

## Objectives

- Design a non-invasive neonatal monitoring system.
- Estimate bilirubin and glucose levels using optical sensing.
- Develop a portable embedded platform based on ESP32.
- Implement real-time signal acquisition and processing.
- Provide an affordable point-of-care diagnostic solution.

---

## System Architecture

```text
Multi-Wavelength LEDs
          │
          ▼
    Neonatal Tissue
          │
          ▼
 Silicon PIN Photodiode
          │
          ▼
 Transimpedance Amplifier
          │
          ▼
      ESP32 ADC
          │
          ▼
 Signal Processing
          │
          ▼
 OLED Display Output
```

---

## Working Principle

1. Multi-wavelength light is directed onto neonatal tissue.
2. Tissue absorbs light differently based on bilirubin and glucose concentration.
3. Reflected optical signals are captured using a silicon PIN photodiode.
4. Signals are amplified through a transimpedance amplifier.
5. The ESP32 acquires the analog signal through its ADC.
6. Signal processing algorithms estimate glucose and bilirubin concentrations.
7. Results are displayed in real time on an OLED display.

---

## Hardware Components

| Component | Purpose |
|------------|------------|
| ESP32 Microcontroller | Data acquisition and processing |
| Multi-Wavelength LEDs | Optical illumination |
| Silicon PIN Photodiode | Optical signal detection |
| Transimpedance Amplifier | Signal conditioning |
| ADC | Analog-to-digital conversion |
| OLED Display | Real-time output display |
| Power Supply | System operation |

---

## Software Components

- Arduino IDE
- Embedded C/C++
- ESP32 Development Framework
- Signal Processing Algorithms
- OLED Display Libraries

---

## Repository Structure

```text
Neonatal-Glucose-Bilirubin-Detection
│
├── ESP32_Code
│   ├── ESP32_Main.ino
│   ├── SignalProcessing.h
│   ├── SignalProcessing.cpp
│   ├── Display.h
│   └── Display.cpp
│
├── Images
│   ├── Setup.jpg
│   └── Output.jpg
│
├── Report
│   └── REPORT.pdf
│
└── README.md
```

---

## Hardware Setup

![Hardware Setup](Images/Setup.jpg)

---

## Experimental Output

![Output](Images/Output.jpg)

---

## Software Implementation

### Main Controller

**ESP32_Main.ino**

Responsible for:

- Sensor initialization
- Data acquisition
- Signal processing
- OLED display control

### Signal Processing Module

**SignalProcessing.h / SignalProcessing.cpp**

Functions include:

- Sensor voltage acquisition
- ADC data conversion
- Bilirubin estimation
- Glucose estimation
- Signal conditioning

### Display Module

**Display.h / Display.cpp**

Functions include:

- OLED initialization
- Real-time display updates
- User interface handling

---

## Key Features

✅ Non-invasive measurement

✅ Real-time monitoring

✅ Portable embedded platform

✅ Low-cost implementation

✅ OLED-based display interface

✅ Biomedical signal processing

✅ Point-of-care diagnostics

---

## Applications

- Neonatal Intensive Care Units (NICU)
- Pediatric Healthcare Monitoring
- Point-of-Care Diagnostics
- Rural Healthcare Centers
- Home-Based Neonatal Monitoring
- Biomedical Research

---

## Advantages

- Eliminates repeated blood sampling
- Reduces neonatal discomfort
- Portable and lightweight
- Cost-effective solution
- Suitable for continuous monitoring
- Easy deployment in resource-limited settings

---

## Future Scope

- IoT-based remote monitoring
- Mobile application integration
- Cloud-based data storage
- AI-assisted calibration models
- Wireless communication modules
- Wearable neonatal monitoring systems
- Clinical validation on larger datasets

---

## Project Report

The complete project documentation is available in the Report folder.

📄 **Project Report:**  
`Report/REPORT.pdf`

---

## Results

The developed prototype successfully demonstrates the feasibility of estimating neonatal glucose and bilirubin concentrations using non-invasive optical sensing techniques. The system performs real-time acquisition, processing, and display of optical measurements using an ESP32-based embedded platform.

---

## Technologies Used

- Biomedical Instrumentation
- Optical Biosensing
- Embedded Systems
- ESP32
- Arduino IDE
- Signal Processing
- OLED Display Technology
- Point-of-Care Diagnostics

---

## Authors

### Janasruthika P R
Bachelor of Engineering – Biomedical Engineering  
Bannari Amman Institute of Technology

### Jeevika Harshine S
Bachelor of Engineering – Biomedical Engineering  
Bannari Amman Institute of Technology

---

## Institution

Department of Biomedical Engineering  
Bannari Amman Institute of Technology  
Sathyamangalam, Tamil Nadu, India

---

## License

This repository is intended for academic, educational, and research purposes.

---

### Acknowledgement

We express our sincere gratitude to the Department of Biomedical Engineering, Bannari Amman Institute of Technology, for providing guidance, resources, and support throughout the development of this project.
