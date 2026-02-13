# LPC2148 UART Serial Communication

## 📌 Project Overview

This project demonstrates UART0 based serial communication using the LPC2148 (ARM7) microcontroller.

The program initializes UART0 and continuously transmits the message:

HELLO WORLD

over serial communication.

---

## 🎯 Objective

To understand and implement UART communication on ARM7 (LPC2148) using:

- UART0 configuration
- Register-level programming
- Polling-based transmission
- Serial communication debugging

---

## ⚙️ Working Principle

1. VPBDIV is configured to set peripheral clock.
2. PINSEL0 is configured to enable UART0 pins.
3. UART0 is initialized:
   - 8-bit data
   - No parity
   - 1 stop bit
4. Baud rate is configured using U0DLL.
5. UART continuously transmits "HELLO WORLD" using polling method.

---

## 🔧 Hardware Used

- LPC2148 (ARM7) Microcontroller
- 60 MHz Clock
- Serial Terminal (Proteus / PC Serial Monitor)
- Keil / Embedded C Compiler

---

## 🧠 Concepts Applied

- ARM7 register-level programming
- UART0 configuration (U0LCR, U0DLL, U0THR, U0LSR)
- Baud rate setup
- PIN function selection using PINSEL0
- Polling-based transmission
- Peripheral clock configuration (VPBDIV)

---

## 📂 Repository Structure


---

## 🚀 Possible Enhancements

- Implement UART reception
- Echo received characters
- Convert to interrupt-based UART
- Interface with Bluetooth module
- Integrate with LCD display

---

## 📈 Learning Outcome

This project strengthens understanding of:

- ARM microcontroller peripheral configuration
- Serial communication on embedded platforms
- Low-level register manipulation
- Embedded firmware development using C
