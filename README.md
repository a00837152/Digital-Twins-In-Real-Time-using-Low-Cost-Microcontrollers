# Digital-Twins-In-Real-Time-using-Low-Cost-Microcontrollers
Simulink examples and Real-Time implementation models used in the book chapter "Digital Twins In Real-Time using Low Cost Microcontrollers", focusing on the Texas Instruments C2000 platform (F28379D Launchpad.

This repository contains the Simulink models and implementation examples developed as part of the book chapter.

The chapter presents a reproducible and modular approach for deploying Real-Time Simulationimplementations on low-cost embedded systems, specifically the Texas Instruments C2000 microcontroller family.

---

## 📂 Contents

- `models/` — Simulink models of the physical and virtual systems (e.g., power stage, thermal system, motion system)
- `target/` — Configurations for deployment on TI F28379D LaunchPad
- `scripts/` — Helper scripts for tuning and interfacing
- `figures/` — Images and diagrams used in the book chapter

---

## 🛠 Requirements

To run or adapt these models, you must have:

- MATLAB and Simulink (R2022b or newer recommended)
- Embedded Coder
- **C2000 Support Package for Simulink**
- **C2000Ware** (from Texas Instruments)
- **Code Composer Studio (CCS)**

A step-by-step setup of the required toolchain is described in detail in "Introduction to Microcontroller Programming for Power Electronics Control Applications"

---

## 📌 Key Features

- Real-Time Simulation of DC Motor Model
- Real-Time Simulation of power electronics (Buck converter)
- Integration with C2000 hardware using Simulink blocks
- Digital twin modeling with adequate fidelity for real-time constraints

---

## ⚠️ Disclaimer

This repository is intended for educational and research purposes. All models are provided “as is” and may require further tuning depending on your target hardware or application.

