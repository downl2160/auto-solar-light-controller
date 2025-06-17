# 🌞 Auto Solar Street Light Controller (Analog)

A simple, analog street lighting system that automatically turns lights ON at night and OFF during daylight using an LDR-based sensing mechanism. Built entirely using analog components (no microcontroller or code), the project showcases the use of voltage dividers, comparators, and relay-based switching.

---

## ✅ Features

- Lights turn ON automatically when ambient light is low (night)
- Lights turn OFF when sunlight is sufficient (day)
- Built with **only analog components** — no coding required
- Energy-efficient, cost-effective solution for rural or small-scale implementations

---

## 🛠️ Components Used

| Component                     | Purpose                                              |
|-------------------------------|------------------------------------------------------|
| **LDR (Light Dependent Resistor)** | Detects ambient light level                         |
| **LM358 Comparator (Op-Amp)** | Compares voltage from LDR with reference threshold   |
| **Relay Module / Transistor** | Switches high-voltage light ON/OFF                  |
| **Resistors / Potentiometer** | Sets sensitivity and threshold levels               |
| **Power Supply (5V/12V)**     | Powers the analog logic and relay coil              |
| **Breadboard / PCB**          | Circuit assembly and testing platform               |

---

## 🔧 Circuit Diagrams

- [Download Schematic](./circuit/schematic.png)  
- [View Simulation (if available)](./circuit/simulation.jpg)

> The schematic illustrates the voltage divider formed by the LDR and fixed resistor, feeding into a comparator that toggles the relay.

---

## 📸 Prototype

- [View Breadboard/Prototype Photo](./images/prototype_photo.jpg)

This image shows the actual implementation with relay, op-amp, LDR sensor, and LED/lamp as output.

---

## 🎓 Learning Outcomes

- Analog sensing and threshold switching
- Comparator-based decision logic (LM358)
- Use of relays/transistors to control AC/DC loads
- Real-world application of LDR-based control systems

---

## 📜 License

This project is licensed under the [MIT License](./LICENSE).

---

> Developed by **Siddharth Singh**  
> Part of core electrical project showcase for energy-efficient automation.
