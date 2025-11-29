# SmartHomeAutomation

---

## Project Description
This project simulates a smart home automation system using **Tinkercad**. It integrates multiple sensors to monitor the environment and control devices automatically. The system can detect motion, monitor light levels, detect gas leaks, and operate a door with a servo motor. The Arduino Uno reads sensor data and controls outputs like LEDs, relays, a buzzer, and a servo motor.

---

## Components Used
- Arduino Uno  
- LDR (Light Sensor)  
- PIR Motion Sensor  
- MQ-2 Gas Sensor  
- HC-SR04 Ultrasonic Sensor  
- SG90 Servo Motor  
- Buzzer  
- Relay Module  
- LEDs  
- Breadboard  
- Jumper Wires  

---

## Circuit Diagram
The circuit is built on a breadboard and connected to an **Arduino Uno**. Sensors and actuators are wired as follows:

**LDR (Light Sensor):**  
- One leg → 5V  
- Other leg → A0 (Analog Input) with 10kΩ pull-down resistor to GND  

**PIR Sensor:**  
- VCC → 5V  
- GND → GND  
- OUT → Digital Pin 9  

**MQ-2 Gas Sensor:**  
- VCC → 5V  
- GND → GND  
- A0 → Analog Pin A1  

**Ultrasonic Sensor (HC-SR04):**  
- VCC → 5V  
- GND → GND  
- Trig → Digital Pin 6  
- Echo → Digital Pin 7  

**Servo Motor (SG90):**  
- Power → 5V  
- GND → GND  
- Signal → Digital Pin 7  

**Buzzer:**  
- Positive → Digital Pin 8  
- Negative → GND  

**Relay Module (for lights/fan):**  
- Input → Digital Pin 10  
- VCC → 5V  
- GND → GND  

**LEDs:**  
- Red LED → Pin 4  
- Green LED → Pin 3  
- Current-limiting resistor → 220Ω  

**Power Supply:**  
Arduino is powered via USB.

---

## What I Learned
- **Basic Electronics Concepts:** Understanding sensors, actuators, wiring, resistors, and breadboards.  
- **Arduino Programming:** Reading sensor data, converting values, controlling outputs, and using libraries.  
- **Simulation Skills:** Testing and debugging circuits virtually in Tinkercad before physical implementation.  
- **Problem Solving:** Identifying and fixing wiring or code issues effectively.

---

## Tinkercad Project
Add your Tinkercad link here:  
https://www.tinkercad.com/things/kJGdvfpz5cU-powerful-amberis

---

## Folder Structure
