# Neonatal-Glucose-Bilirubin-Detection
Non-invasive optical sensing system for bilirubin and glucose monitoring in neonates using ESP32 and multi-wavelength spectroscopy.
# Detection of Glucose and Bilirubin in Neonates

## Overview

This project presents a portable, low-cost, and non-invasive optical sensing system for estimating glucose and bilirubin levels in neonates. The system utilizes multi-wavelength optical spectroscopy, photodetection, and embedded processing to provide real-time measurements without requiring invasive blood sampling.

## Motivation

Neonatal hypoglycemia and jaundice are common conditions that require continuous monitoring. Conventional diagnostic methods involve blood collection, which can be painful and impractical for frequent measurements. This project aims to provide a safer and more comfortable alternative.

## System Components

* Multi-wavelength LED sources
* Silicon PIN Photodiode
* Transimpedance Amplifier
* High Resolution ADC
* ESP32 Microcontroller
* OLED Display

## Working Principle

1. Light is transmitted into neonatal tissue.
2. Tissue absorption characteristics vary with glucose and bilirubin concentration.
3. Reflected light is detected by a silicon PIN photodiode.
4. The signal is amplified and digitized.
5. ESP32 processes the data using the Modified Beer–Lambert Law.
6. Estimated values are displayed on an OLED screen.

## Features

* Non-invasive measurement
* Portable design
* Real-time monitoring
* Low-cost implementation
* Suitable for neonatal care environments

## Technologies Used

* ESP32
* Embedded C / Arduino IDE
* Optical Biosensing
* Biomedical Signal Processing
* Modified Beer–Lambert Law

## Applications

* Neonatal Intensive Care Units (NICU)
* Point-of-Care Diagnostics
* Remote Healthcare Monitoring
* Resource-Limited Clinical Settings

## Authors

Janasruthika P R
Jeevika Harshine S

Biomedical Engineering
Bannari Amman Institute of Technology
