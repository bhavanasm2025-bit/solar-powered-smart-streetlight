# Solar-Powered Smart Streetlight

## 1. Introduction

The Solar-Powered Smart Streetlight is a simulation-based project that automatically controls streetlight brightness using light and motion sensors.

## 2. Problem Statement

Streetlights may use unnecessary energy when full brightness is not required. This project demonstrates automatic lighting control based on surrounding light and movement.

## 3. Objectives

- Detect day and night using an LDR sensor.
- Detect movement using a PIR sensor.
- Turn the LED OFF during daytime.
- Keep the LED DIM at night when no movement is detected.
- Increase brightness when movement is detected.

## 4. Components Used

- Arduino Uno
- LDR sensor
- PIR motion sensor
- LED
- 220-ohm resistor
- 10k-ohm resistor
- Breadboard and jumper wires
- Solar panel and battery as the proposed power-system concept

## 5. Working Principle

The LDR detects the surrounding light level. The PIR sensor detects movement. The Arduino processes these inputs and controls the LED.

- **Daytime:** LED OFF.
- **Night with no movement:** LED DIM.
- **Night with movement:** LED BRIGHT.

## 6. Simulation

The circuit will be simulated using Tinkercad.

**Tinkercad Link:** To be added after the circuit is completed.

## 7. Testing

The project will be tested under three conditions:

1. **Bright environment:** LED should be OFF.
2. **Dark environment without movement:** LED should be DIM.
3. **Dark environment with movement:** LED should be BRIGHT.

Actual test results and screenshots will be added after testing.

## 8. Future Enhancements

- Use a real solar panel and rechargeable battery.
- Add battery-level monitoring.
- Connect multiple streetlights.
- Add IoT-based monitoring.

## 9. Team Responsibilities

- **Member 1:** Circuit design and Tinkercad simulation.
- **Member 2:** Arduino programming.
- **Member 3:** GitHub management, documentation, and presentation.

## 10. Conclusion

This project demonstrates how light and motion sensors can control streetlight brightness automatically. The simulation illustrates a possible approach to reducing unnecessary lighting.
