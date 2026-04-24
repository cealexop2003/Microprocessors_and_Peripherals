# Microprocessors & Peripherals Projects (ARM Cortex-M4)

This repository contains a series of three projects developed for the *Microprocessors and Peripherals* course, focusing on low-level programming, embedded systems design, and real-time control using an ARM Cortex-M4 microcontroller (NUCLEO board).

## 🔧 Technologies
- C & ARM Assembly
- Keil uVision
- UART Communication
- Timers & Interrupts
- Embedded Peripherals (LED, Button, Touch Sensor, DHT11)

---

## 📁 Project Overview

### 🧮 Project 1 – String Hashing in Assembly
- Implemented a custom hashing algorithm in ARM Assembly.
- Processed alphanumeric input via UART and applied:
  - ASCII-based transformations
  - Lookup tables for digit mapping
  - Digit summation and modulo reduction
  - Recursive Fibonacci computation
- Integrated C and Assembly routines for full system execution. :contentReference[oaicite:0]{index=0}

---

### ⏱️ Project 2 – Real-Time Number Analysis with Interrupts
- Developed an interrupt-driven system for analyzing numeric input via UART.
- Used timers to process digits sequentially in real time.
- Controlled LED behavior based on digit parity (blink/toggle).
- Implemented button interrupts with priority handling and system state locking.
- Supported dynamic input interruption and continuous looping modes. :contentReference[oaicite:1]{index=1}

---

### 🌡️ Project 3 – Environmental Monitoring System
- Built a real-time embedded system using sensors and peripherals.
- Integrated DHT11 sensor for temperature and humidity monitoring.
- Designed a UART-based interactive menu system.
- Implemented:
  - Multiple operating modes (Normal / Alert)
  - Dynamic sampling rate adjustments
  - Touch sensor-based profile switching
  - Safety mechanisms (panic reset on critical conditions)
- Ensured robust real-time behavior using interrupts and event-driven logic. :contentReference[oaicite:2]{index=2}

---

## 🚀 Getting Started
1. Open the project in **Keil uVision**.
2. Select the **NUCLEO-M4** board.
3. Build and run the project.
4. Use a serial terminal (e.g., **Tera Term**) for UART interaction.

---

## 📌 Notes
- All projects emphasize real-time system design and hardware-software interaction.
- Code is modular, combining C and Assembly where appropriate.
- Designed and tested in a simulated embedded environment.

---

## 👤 Author
Christos Alexopoulos
