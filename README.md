
# 🚀 Stair Glider – Microcontroller-Based Stair Assist System

A smart assistive stair glider designed to help physically challenged and elderly people navigate residential staircases with ease, using an **ATmega32** microcontroller, sensors, display, and actuators.

---

## 🧠 Project Overview

This system facilitates vertical transportation within residential buildings where elevators may not be viable. It provides a safe, compact, and low-power solution to support:

- Elderly people  
- Individuals with physical disabilities  
- Compact apartment stairwells  

### 🔑 Key Features

- Microcontroller-based automated system  
- Directional control with push buttons  
- Obstacle detection using IR sensors  
- Visual instructions via LCD display  
- Alerts using buzzer signals  
- Relay-controlled motor for motion  

---

## 🔧 Hardware Components Used

| **Component**       | **Description**                                           |
|---------------------|-----------------------------------------------------------|
| Microcontroller     | ATmega32 (RISC-based, brain of the system)               |
| DC Motor            | 10 RPM geared motor for chair movement                   |
| Relay Module        | Controls motor direction via microcontroller             |
| LCD Display         | Displays real-time status and user instructions          |
| Push Buttons        | Allows user to initiate up/down movement                 |
| IR Sensors          | Detects obstacles on the staircase                       |
| Buzzer              | Alerts when an obstacle is detected or floor is reached  |
| Adapters            | 5V-2A for motors and 12V-2A for microcontroller          |

---

## ⚙️ Tools and Software Used

| **Tool / Software**           | **Purpose**                                   |
|-------------------------------|-----------------------------------------------|
| Proteus                       | Circuit simulation and design                 |
| AVR Studio / Atmel Studio     | Microcontroller programming and debugging     |
| Embedded C                    | Firmware development                          |
| KiCAD / Eagle                 | PCB design (if applicable)                    |
| Serial Monitor / LCD GUI      | Display output simulation                     |
| Breadboard & Soldering Tools  | Hardware prototyping                          |

---

## 🔁 How It Works (System Workflow)

1. User presses **Up/Down** button.  
2. **Microcontroller (ATmega32)** receives input and activates the **relay**.  
3. Relay controls the **DC motor direction**, moving the chair.  
4. **IR Sensors** monitor path for obstacles.  
5. If obstacle is detected:  
   - **Buzzer** rings.  
   - Motion is halted.  
6. Once desired position is reached:  
   - **Buzzer** rings.  
   - **LCD** displays confirmation.  

---

## 🧱 Block Diagram

```

\[ Push Buttons ]
↓
\[ ATmega32 Microcontroller ] ← \[ IR Sensors ]
↓                     ↑
\[ Relay Switch ] → \[ DC Motor (Chair Movement) ]
↓
\[ LCD Display & Buzzer ]

```

---

## 💡 Motivation & Problem Statement

Residential buildings often lack elevator systems, making vertical mobility difficult for elderly and physically disabled individuals. Our system provides:

- A compact stair-lift system  
- Enhanced safety via obstacle detection  
- Clear user guidance through LCD messages  
- Simple and affordable implementation  

---

## 👨‍💻 Team Members

- **Prashant U.**  
- **Chandni**  
- **Yukta S.**  
- **Wilfred B.**  

**Team No:** A11  
**Department:** CSE & CSE (AI)  

---

## 📜 License

This project is open-source and available under the [MIT License](./LICENSE).

---

## 🤝 Acknowledgements

- KLE Technological University – Dept. of CSE & CSE (AI)  
- Faculty mentors and lab assistants  
- Arduino, AVR Freaks, and open-source embedded communities  

---

## 🔗 Project Files

- [📦 Download Full Project Files (Code + Circuit)](./stair_glider.zip)  
- [📽️ Project Presentation (PPT)](./A_11_stair_glider.pptx)  

