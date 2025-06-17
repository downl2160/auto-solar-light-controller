# 🌞 Auto Solar Street Light Controller

An automatic street lighting system designed using an LDR (Light Dependent Resistor) and optional IR sensor. This project turns the light ON during low ambient light (e.g., night) and OFF during the day — simulating real-world energy-efficient solar streetlights. Motion-triggered brightening using IR sensor is optionally supported.

---

## ✅ Features

- Automatic **night ON / day OFF** functionality using LDR
- Optional **motion-based activation** using IR sensor
- Simple analog circuit with **op-amp comparator logic**
- Can be implemented with **relay or transistor-based switching**
- Cost-effective and ideal for school, rural, or academic demos

---

## 🛠️ Technologies & Components Used

| Component                        | Purpose                                                 |
|----------------------------------|---------------------------------------------------------|
| **LDR**                          | Detects ambient light (day/night threshold)             |
| **IR Sensor (optional)**         | Detects motion to activate or brighten the lamp         |
| **Relay Module / Transistor**    | Acts as the switching device for AC/DC load             |
| **LM358 / Comparator Op-Amp**    | Converts analog LDR signal to ON/OFF logic              |
| **Power Supply (5V/12V)**        | Drives logic circuit and switching component            |
| **Breadboard / PCB**             | Circuit assembly and testing                            |

---

## 🔧 Circuit

A simplified conceptual schematic is available:

📁 `circuit/schematic.png`  
> *(Add your real schematic image to this path)*

---

📁 `code/ldr_ir_lamp_control.ino`  
- Demonstrates LDR + IR logic  
- Switches a digital pin (for relay/transistor control)

---

## 📸 Prototype Images

📁 `images/` contains real photos of the working prototype.  
> *(e.g., breadboard setup, IR placement, relay switching, etc.)*

---

## 🎓 Learning Outcomes

- Analog signal sensing with LDR
- Comparator threshold switching (LM358)
- Relay/transistor switching for AC/DC loads
- Understanding of day-night automation
- Optional: motion-triggered lighting via IR sensor

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

> Created by **Siddharth Singh** — for academic and energy-efficiency applications.  
