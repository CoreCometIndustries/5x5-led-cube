

# 💡 5×5×5 LED Cube using Arduino Nano

## 📌 Project Description

The **5×5×5 LED Cube** is a three-dimensional LED display system consisting of **125 LEDs** arranged in a cubic matrix.
The project demonstrates **multiplexing**, **persistence of vision**, and **real-time animation control** using an **Arduino Nano**.

By rapidly switching LED layers and columns, the cube creates the illusion of fully illuminated 3D patterns while using a limited number of microcontroller pins. This project is ideal for understanding **embedded systems, timing control, and digital electronics**.

---

## ✨ Features

* 🔲 **5×5×5 (125 LEDs) 3D Matrix**
* ⚡ **Layer-by-layer multiplexing**
* 🎞️ **Multiple 3D animations**
* ⏱️ **Adjustable animation speed**
* 🔌 **Optimized GPIO usage**
* 🔁 **Smooth refresh without flicker**
* 🧠 Demonstrates **persistence of vision**

---

## 🧠 Working Principle

* The LED cube is divided into **5 horizontal layers**
* Only **one layer is powered at a time**
* Columns are switched rapidly using Arduino GPIOs
* Due to **high refresh speed**, the human eye perceives a continuous 3D image
* Transistors or driver ICs handle higher current safely

---

## 🧰 Hardware Requirements

| Component                 | Quantity    |
| ------------------------- | ----------- |
| Arduino Nano              | 1           |
| LEDs                      | 125         |
| Resistors (220Ω / 330Ω)   | As required |
| NPN Transistors / ULN2803 | 5           |
| Breadboard / PCB          | 1           |
| 5V Power Supply           | 1           |

---

## 🖥️ Software Requirements

* Arduino IDE
* Arduino Nano Board Package
* Basic C/C++ knowledge

---

## 🔌 Pin Configuration (Example)

| Function       | Arduino Nano Pin  |
| -------------- | ----------------- |
| Layer Control  | D2 – D6           |
| Column Control | D7 – D13, A0 – A4 |
| Power          | 5V                |
| Ground         | GND               |

> ⚠️ Pin assignments may vary based on your wiring design.

---

## 🎮 Animations Implemented

* 🔼 Layer Sweep (Top → Bottom)
* 🔽 Layer Sweep (Bottom → Top)
* 🌧️ Rain / Falling LED Effect
* 🔳 Cube Expand & Collapse
* ✨ Random Sparkle
* ➕ Plane Shift (X, Y, Z)

---

## 🚀 How to Run

1. Assemble the LED cube carefully
2. Connect layers and columns as per wiring
3. Upload the Arduino code
4. Power the system with 5V
5. Observe 3D animations

---

## 🧪 Applications

* Embedded systems learning
* Digital electronics demonstration
* STEM education
* Visual animation experiments
* College mini / major project
* Display and art installations

---

## 🔮 Future Enhancements

* Bluetooth or WiFi control
* Sound-reactive animations
* Mobile app control
* Larger cube size (8×8×8)
* Shift-register based design

---

## 👨‍💻 Author

**Bhushan Patil**
Core Comet Industries 🚀
Embedded Systems | Robotics | Electronics

---

## 📜 License

This project is intended for **educational and personal use**.
Commercial use requires prior permission.

---


