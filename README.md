# 5V USB-Powered High-Voltage Igniter Module

A DIY hardware project exploring step-up transformers and plasma generation using a modified electronic gas igniter powered by a 5V USB input.

---

## ⚠️ CRITICAL SAFETY WARNING & DISCLAIMER

> **IMPORTANT:** High-voltage projects carry inherent risks of electrical shock, severe burns, and fire. This documentation is for educational purposes only. 

* **Fire Hazard:** High-voltage plasma arcs reach extreme temperatures (over 1,000°C). **NEVER** operate this device on or near flammable materials such as bedding, mattresses, clothing, or wooden surfaces.
* **Mains Isolation:** Do not plug this device into a standard wall adapter. High-voltage feedback can travel backward and destroy the adapter or cause a dangerous mains short circuit. 
* **Safe Handling:** Always completely unplug the power source and discharge the circuit before touching any wires or adjusting the spark gap electrodes.

---

## ⚙️ How It Works

This project repurposes a commercial electronic gas igniter module to create a visible electrical plasma arc:
1. **Input:** A 5V DC power source is supplied via a spliced USB cable.
2. **Amplification:** The internal solid-state switching circuit and flyback transformer step up the low voltage to several thousand volts.
3. **Output:** The high-voltage current outputs through the **HVI** and **HVII** terminals, ionizing the air gap to create a continuous electrical arc.

---

## 🛠️ Project Setup & Best Practices

To document or rebuild this project safely, ensure the following guidelines are met:

### 1. Isolated Power Supply
* **Recommended:** Use a portable USB battery power bank instead of a wall outlet. If the circuit experiences high-voltage feedback, it will only damage the replaceable power bank, keeping your home's electrical system completely isolated and safe.

### 2. Non-Flammable Testing Workspace
* Only operate the module on a strictly non-flammable surface, such as:
  * A ceramic tile
  * A concrete floor (e.g., garage or balcony)
  * A large, isolated metal baking tray

### 3. Proper Wire Insulation
* Ensure all custom wire splices, exposed copper strands, and loose spade connectors are heavily wrapped in high-quality electrical tape or heat-shrink tubing to prevent accidental short circuits.

---

## 📂 Repository Structure

* `/images` - Contains photos and diagrams of the module wiring connections.
* `README.md` - Main project documentation and safety guidelines.
# usb-high-voltage-igniter
