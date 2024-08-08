# Interactive Object Detection System

## Overview

This Interactive Object Detection System integrates various components to measure distances, manage light intensity, and handle IR remote commands. The system uses an ultrasonic sensor for distance measurement, a photoresistor for light intensity detection, and an LCD for displaying information. It also interacts with users through an IR remote and button presses.

## Features

- **Distance Measurement:** Uses an ultrasonic sensor to measure distances.
- **Warning and Error Indicators:** LEDs provide visual warnings and errors based on distance measurements.
- **Light Intensity Management:** Adjusts LED brightness based on ambient light detected by a photoresistor.
- **User Interaction:** Supports control through an IR remote and a physical button.
- **LCD Display:** Provides real-time feedback and settings through a LiquidCrystal display.

## Components

- **Ultrasonic Sensor** (HC-SR04)
- **IR Remote Receiver**
- **Photoresistor**
- **LEDs** (Warning, Error, Light)
- **LCD Display** (16x2)
- **Button**
- **Arduino Board** (e.g., Arduino Uno)

## Wiring

- **IR Receiver**: Connected to pin 5
- **Ultrasonic Sensor**: 
  - Echo pin to pin 3
  - Trigger pin to pin 4
- **LEDs**: 
  - Warning LED to pin 11
  - Error LED to pin 12
  - Light LED to pin 10
- **Button**: Connected to pin 2
- **Photoresistor**: Connected to analog pin A0
- **LCD**: 
  - RS to A5
  - E to A4
  - D4 to pin 6
  - D5 to pin 7
  - D6 to pin 8
  - D7 to pin 9

