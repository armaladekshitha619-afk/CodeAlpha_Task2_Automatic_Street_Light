# Automatic Street Light Using Arduino and LDR

## CodeAlpha IoT Internship – Task 2

### Project Overview

This project demonstrates an Automatic Street Light System using an Arduino Uno and an LDR (Light Dependent Resistor). The system automatically turns an LED ON when the surrounding light intensity decreases and turns it OFF when sufficient light is available.

---

## Objective

- Design a sensor-based lighting system.
- Simulate the project using Tinkercad.
- Control an LED automatically using an LDR sensor.

---

## Components Used

- Arduino UNO
- LDR (Light Dependent Resistor)
- LED
- 220 Ω Resistor
- 10 kΩ Resistor
- Jumper Wires

---

## Circuit Diagram

![Circuit Diagram](Circuit_Diagram.png)

---

## Working Principle

The LDR changes its resistance according to the amount of light falling on it. The Arduino continuously reads the analog value from the LDR. If the value falls below the threshold, the LED turns ON automatically. Otherwise, it remains OFF.

---

## Simulation Results

### LED ON (Dark Environment)

![LED ON](LED_ON.png)

### LED OFF (Bright Environment)

![LED OFF](LED_OFF.png)

---

## Arduino Code

The Arduino source code is available in:

**Automatic_Street_Light.ino**

---

## Applications

- Automatic Street Lights
- Smart Home Lighting
- Garden Lighting
- Parking Area Lighting
- Energy Efficient Lighting Systems

---

## Conclusion

This project demonstrates a simple, low-cost, and energy-efficient automatic lighting system using Arduino and an LDR sensor. It highlights the practical application of IoT concepts in smart lighting solutions.

---

## Internship

**CodeAlpha – Internet of Things (IoT) Internship**
