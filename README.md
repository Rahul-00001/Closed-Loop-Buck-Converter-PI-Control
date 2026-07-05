# Closed-Loop Buck Converter Using PI Control

Design, modeling, and control of a closed-loop buck converter using state-space averaging and PI control. The project includes converter design, small-signal modeling, frequency-domain controller design, MATLAB/Simulink implementation, LTspice validation, and performance evaluation under line, load, and reference variations.

---

## Overview

This project presents the complete design and validation of a closed-loop buck converter capable of maintaining a regulated output voltage under varying operating conditions. The converter was analytically designed, modeled using the state-space averaging technique, and controlled using a PI controller designed through frequency-domain loop shaping. The complete closed-loop system was implemented in MATLAB/Simulink and verified through LTspice simulations.

---

## Key Features

- Analytical buck converter design
- Continuous Conduction Mode (CCM) operation
- Small-signal state-space averaged modeling
- Control-to-output transfer function derivation
- PI controller design using frequency-domain techniques
- MATLAB/Simulink implementation
- LTspice validation
- Steady-state performance evaluation
- Static and dynamic reference tracking
- Line regulation and load regulation analysis

---

## Design Specifications

| Parameter | Value |
|-----------|------:|
| Input Voltage | 24 V |
| Output Voltage | 12 V |
| Rated Output Current | 2 A |
| Rated Load Resistance | 6 Ω |
| Switching Frequency | 100 kHz |
| Inductor | 150 μH |
| Capacitor | 10 μF |
| Controller | PI |
| Operating Mode | CCM |

---

## Project Workflow

```text
Buck Converter Design
        ↓
Open-Loop Validation
        ↓
Small-Signal Modeling
        ↓
PI Controller Design
        ↓
Closed-Loop Implementation
        ↓
Performance Evaluation
```

---

## Results

<img width="2187" height="1262" alt="Dynamic_V_Ref" src="https://github.com/user-attachments/assets/c6bd3ee2-9393-489a-8ac3-b69524af3285" />

*Dynamic reference tracking demonstrating accurate regulation of the output voltage over multiple reference voltage changes.*

---

## Repository Contents

- 📄 **Project_Report.pdf** – Complete project documentation
- 📁 **Simulink_Models** – Open-loop and closed-loop MATLAB/Simulink models
- 📁 **LTspice_Model** – LTspice implementation of the buck converter

---

## Software Used

- MATLAB
- Simulink
- LTspice

---

## Future Work

- Hardware implementation using a microcontroller or DSP
- PCB design and fabrication
- Digital control implementation
- Investigation of advanced control techniques
- Experimental validation under practical operating conditions

---

## Author

**Rahul Kumar Pandey**  
B.Tech Electrical Engineering  
Punjab Engineering College (PEC), Chandigarh

**Areas of Interest**

- Control Systems
- Power Electronics
- Electric Drives
