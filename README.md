# 🌿 Fully Analog Plant Monitoring and Control System

Welcome to the **Fully Analog Plant Monitoring and Control System** — a robust, electricity-free solution for monitoring and regulating environmental conditions for indoor and outdoor plants. This system uses no microcontrollers or digital electronics, making it ideal for off-grid applications, sustainability enthusiasts, or education in basic electronics and fluid dynamics.

## 📦 Project Overview

This system provides real-time feedback and control using analog sensors and mechanical or passive actuators. It can be used to monitor soil moisture, ambient light, temperature, and other environmental conditions, and to automate actions like watering or adjusting shade.

### Key Features

- **No microcontrollers or digital components**
- Fully passive/analog sensing and control
- Works without code or electricity (or with minimal power where necessary)
- Easy to build, repair, and scale
- Environmentally sustainable and educational

## 🛠️ System Components

The exact components may vary depending on your design, but here are typical modules used in this analog system:

| Module | Description |
|--------|-------------|
| **Soil Moisture Sensor** | Passive resistive/capacitive probes triggering relays or water flow via mechanical/hydraulic means |
| **Light Sensor** | Light-dependent resistor (LDR) to measure ambient light and actuate shading mechanisms |
| **Thermal Sensor** | Bimetallic strips or thermistors used to trigger ventilation |
| **Watering Mechanism** | Gravity-fed system triggered by soil sensor or pressure-based mechanism |
| **Power (optional)** | Solar cell or battery to power low-current analog components like op-amps (if used) |
| **Control Interface** | Mechanical switches, dials, or pressure valves for setting thresholds |

## 🔧 Example Use Case

Here’s how a basic setup might work:

- **Moisture probe** detects dry soil, lowering resistance.
- The lowered resistance activates a **relay** or **thermal switch**.
- This triggers a **gravity-fed watering valve** to release water.
- Once soil is moist, the resistance rises and the valve closes.

All without a single line of code!

## 📐 Schematics & Diagrams

You can find system diagrams in the `/docs/schematics/` folder:

- `basic_system_diagram.png`
- `moisture_sensor_circuit.svg`
- `light_triggered_shade_mechanism.pdf`

> Feel free to contribute your own variations!

## 🚀 Getting Started

1. Review the components list and acquire the necessary analog parts.
2. Assemble the modules according to the included schematics.
3. Calibrate each sensor module manually using dials, mechanical stops, or fluid levels.
4. Test individual modules before integrating into a full system.
5. Observe plant response and fine-tune thresholds as needed.

## 📎 Project Goals

- Explore sustainable, non-digital automation
- Demonstrate the power of analog systems in environmental control
- Provide educational resources for electronics, physics, and botany

## 🤝 Contributing

We welcome designs, photos, and schematics of your own fully analog plant systems! You can submit a pull request or open an issue with your contribution idea.


