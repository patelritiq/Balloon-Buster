# 🎯 Balloon Buster
### A C++ Balloon Shooting Game

A nostalgic, arcade-style implementation of a balloon shooting game developed in **C++** using the legacy `graphics.h` library.

---

## 🚀 Overview
Master your aim with a bow and arrow to pop rising balloons across three increasingly difficult levels. This project demonstrates core concepts of **graphics programming**, **collision detection**, and **real-time user input handling** in a DOS environment.

## 🛠️ Technical Specifications
* **Language:** C++
* **Graphics:** BGI (Borland Graphics Interface) / `graphics.h`
* **Environment:** Turbo C++ 3.0 (Recommended: DOSBox for modern OS)
* **Key Features:**
    * 3 Progression Levels with increasing difficulty.
    * Custom-drawn sprites for Bow, Arrow, and Balloons.
    * Sound effects via the PC speaker (`sound.h`).
    * Manual memory management for image buffers.

---

## 🎮 Game Controls & Rules

| Action | Key |
| :--- | :--- |
| **Move Bow Up** | `Up Arrow` |
| **Move Bow Down** | `Down Arrow` |
| **Shoot Arrow** | `Right Arrow` |
| **Exit Game** | `Q` or `Esc` |

### **Level Progression**
1.  **Level 1:** 6 Arrows | 10 Balloons (Target: 100 points)
2.  **Level 2:** 6 Arrows | 8 Balloons (Target: 200 points)
3.  **Level 3:** 6 Arrows | 6 Balloons (Ultimate Challenge)

> **Scoring:** Each successful hit earns you **20 points**.

---

## 💻 How to Run Locally
1.  Download and install **DOSBox**.
2.  Set up **Turbo C++ 3.0** within the DOSBox environment.
3.  Ensure the BGI path in the source code is correct:
    ```cpp
    initgraph(&gmode, &gdriver, "C:\\TURBOC3\\BGI");
    ```
4.  Copy the source code into the editor and press `Ctrl + F9` to Run.

---

## 👤 Author
Ritik Pratap Singh Patel
