# Closed-Loop Buck Converter Using PI Control

## Project Overview

This project presents the complete design, modeling, control design, implementation, and validation of a closed-loop buck converter using MATLAB/Simulink and LTspice.

The work began with the analytical design of the buck converter followed by open-loop verification. A small-signal state-space averaged model was then developed to derive the control-to-output transfer function. Based on the obtained plant dynamics, a PI controller was designed using frequency-domain loop shaping techniques to satisfy the desired transient and stability specifications.

The complete closed-loop converter was implemented in MATLAB/Simulink and validated through steady-state analysis, reference tracking, line regulation, and load regulation tests.

---

## Key Results

- Closed-Loop Voltage Regulation Achieved
- PI Controller Designed Using Frequency-Domain Loop Shaping
- Gain Margin: 21.94 dB
- Phase Margin: 100.21°
- Settling Time: 0.702 ms
- Overshoot: 0.53 %
- Steady-State Error: 0.0059 %
- Output Voltage Ripple: 45.34 mV
- Line Regulation Verified
- Load Regulation Verified
- Static and Dynamic Reference Tracking Verified

---

## Key Features

- Analytical buck converter design
- Continuous Conduction Mode (CCM) operation
- Small-signal state-space averaged modeling
- Control-to-output transfer function derivation
- PI controller design using frequency-domain loop shaping
- MATLAB/Simulink implementation
- LTspice validation
- Steady-state performance evaluation
- Static reference tracking
- Dynamic reference tracking
- Line regulation analysis
- Load regulation analysis

---

## Design Specifications

| Parameter | Value |
| ------------------------ | ------: |
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

## Controller Design Workflow

```text
Buck Converter Design
          │
          ▼
Open-Loop Validation
          │
          ▼
Small-Signal Modeling
          │
          ▼
PI Controller Design
          │
          ▼
Closed-Loop Implementation
          │
          ▼
Performance Validation
```

---

## Closed-Loop Performance

| Performance Metric | Value |
| ---------------------------- | --------: |
| Output Voltage | 11.999 V |
| Rise Time | 0.272 ms |
| Settling Time | 0.702 ms |
| Overshoot | 0.53 % |
| Steady-State Error | 0.0059 % |
| Output Voltage Ripple | 45.34 mV |
| Inductor Current Ripple | 0.402 A |
| Gain Margin | 21.94 dB |
| Phase Margin | 100.21° |

The designed PI controller achieved fast transient response while maintaining excellent steady-state accuracy and robust regulation under varying operating conditions.

---

## Validation Tests

The following tests were performed:

### Steady-State Performance

- Output voltage regulation
- Output voltage ripple
- Inductor current ripple
- RMS and average value analysis

### Static Reference Tracking

- 3.3 V
- 5 V
- 12 V
- 22 V

### Dynamic Reference Tracking

- 3.3 V → 22 V
- 22 V → 5 V

### Line Regulation

- Input voltage variation
- Automatic duty ratio adjustment
- Output voltage regulation

### Load Regulation

- Load resistance variation
- Output voltage recovery
- Inductor current response
- Duty ratio adaptation

---

## Dynamic Reference Tracking

The figure below demonstrates the closed-loop reference tracking capability of the designed PI controller. The converter successfully follows multiple reference voltage changes while exhibiting fast settling time, low overshoot, and negligible steady-state error.

<img width="2187" height="1262" alt="Dynamic_V_Ref" src="https://github.com/user-attachments/assets/9fa3ccfd-4bc3-46d8-98f1-26374e0f1d2c" />

---

## Tools and Technologies

- MATLAB
- Simulink
- LTspice
- Control System Toolbox
- Frequency-Domain Loop Shaping
- PI Control
- State-Space Averaging

---

## Repository Structure

```text
closed-loop-buck-converter
│
├── README.md
├── Project_Report.pdf
│
├── Simulink_Models
│   ├── Open_Loop_Buck_Converter.slx
│   └── Closed_Loop_Buck_Converter.slx
│
└── LTspice_Model
    └── Buck_Converter.asc
```

---

## Project Report

The complete technical report describing the converter design, mathematical modeling, PI controller design, closed-loop implementation, and performance validation is available in this repository.

📄 [Project Report](Project_Report.pdf)

---

## Future Work

- Hardware implementation using a microcontroller or DSP
- PCB design and fabrication
- Digital controller implementation
- Investigation of advanced control techniques
- Experimental validation using a laboratory prototype

---

## Author

**Rahul Kumar Pandey**

B.Tech Electrical Engineering

Punjab Engineering College (PEC), Chandigarh

**Areas of Interest**

- Control Systems
- Power Electronics
- Electric Drives
