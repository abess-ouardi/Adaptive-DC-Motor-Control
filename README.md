# ⚙️ Adaptive Parameter Estimation and Control of a DC Motor

This project presents the **modeling, control, and adaptive estimation** of a DC motor using advanced control algorithms implemented in MATLAB/Simulink and embedded on a TI **C2000 LaunchPad (F28379D)** with a **BOOSTXL-DRV8305EVM** motor driver.  
The study integrates **cascade PI control**, **feedforward action**, and **adaptive parameter estimation** through **Self-Tuning Regulation (STR)** with **Least Squares Estimation (LSE)**.

---

## 🧠 Overview

The project investigates the complete control architecture of a DC motor system, including:

- Mathematical modeling of electrical and mechanical dynamics  
- Discretization and encoder signal processing  
- Real-time cascade PI control with PWM generation  
- Feedforward and anti-windup integration for improved tracking  
- Online estimation of parameters \( R, L, J, b \) under varying voltages  
- Implementation of **Deadbeat** and **Dahlin** controllers for performance comparison

---

## 🧩 Hardware Setup

- **Microcontroller:** Texas Instruments LAUNCHXL-F28379D  
- **Motor Driver:** BOOSTXL-DRV8305EVM (3-phase gate driver with current sensing and protection)  
- **Motor:** TEM 1524 DC motor (24 V, 1500 RPM nominal)  
- **Encoder:** 2048 PPR quadrature encoder (8192 counts per revolution)

---

## 🔬 Key Topics and Results

| Area | Highlights |
|------|-------------|
| **Modeling** | Electrical and mechanical equations derived, validated with datasheet parameters |
| **Control** | Two-loop PI (current + velocity) structure with adjustable time constants |
| **Filtering** | Encoder signal filtering using low-pass, Tustin, and backward-difference methods |
| **Feedforward / Anti-Windup** | Improved response under saturation and tracking of sinusoidal references |
| **Adaptive Estimation** | Online estimation of R, L, J, b using LSE; validation at 8 V and 24 V |
| **Advanced Controllers** | Deadbeat and Dahlin methods implemented and experimentally tested |

---

## 🧰 Tools and Technologies

- **MATLAB & Simulink**
- **TI C2000 Real-Time Workshop**
- **Simulink Code Generation**
- **Oscilloscope-based data acquisition**
- **Embedded communication dashboards**

---

## 📈 Experimental Highlights

- Validation of adaptive estimation under different loads and voltages  
- Demonstration of anti-windup efficiency in actuator saturation  
- Online adjustment of control parameters using STR logic  
- Smooth tracking of trapezoidal and sinusoidal reference trajectories  

---

## 📄 Full Technical Report

The complete documentation, including mathematical derivations, control design, and experimental results, is available here:

➡️ [**Adaptive_DC_Motor_Control.pdf**](./Adaptive_DC_Motor_Control.pdf)

---

## 🏫 Academic Context

Developed as part of the **Laboratory of Automation Systems** at  
**Alma Mater Studiorum – Università di Bologna**  
**Department of Electrical, Electronic, and Information Engineering (DEI)**  
**Student:** *Abess Ouardi* — *January 2025, Bologna (Italy)*

---

## 🏷️ Keywords / Topics
`adaptive-control` • `parameter-estimation` • `least-squares` • `dc-motor` • `self-tuning-regulator` • `feedforward` • `anti-windup` • `cascade-control` • `matlab` • `simulink`

---

## 📬 Contact

For inquiries or collaboration:
**Abess Ouardi**  
[GitHub](https://github.com/abess-ouardi)

