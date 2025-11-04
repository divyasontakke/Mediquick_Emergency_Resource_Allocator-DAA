# Mediquick_Emergency_Resource_Allocator-DAA
<h1 align="center"> MediQuick: Emergency Resource Allocator</h1>

<p align="center">
  <b>A Smart Emergency Management System for Optimized Ambulance & Hospital Allocation</b>  
  <br>
 
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/GUI-Tkinter-lightgrey" alt="Tkinter">
  <img src="https://img.shields.io/badge/Algorithms-Greedy%20%7C%20DP%20%7C%20Backtracking-brightgreen" alt="Algorithms">
  <img src="https://img.shields.io/badge/License-MIT-yellow" alt="License">
</p>

---

## Overview

**MediQuick** is a smart emergency management system designed to simulate **real-world ambulance and hospital allocation** during medical crises.  
It focuses on **reducing response time** and **maximizing efficiency** using intelligent algorithms and real-time decision-making.

---

##  Problem Statement

Late one evening, a person meets with a serious road accident at a busy intersection in the city. He is badly injured and needs to be taken to a hospital immediately.  
Several ambulances are available across the city, but they are at different distances, some stuck in traffic, and nearby hospitals vary in capacity.

In such situations, manually deciding which ambulance should reach the patient and which hospital should admit them often leads to confusion and delay.  
The nearest ambulance might already be engaged, or the chosen hospital might be full.

To address this, **MediQuick** automatically identifies:
- the **most suitable ambulance** to reach the patient, and  
- the **best hospital** for immediate treatment  

ensuring **fast response time** and **optimal resource allocation**.

---

##  Features

 **Smart Simulation** – Randomly generates hospitals, ambulances, and patients  
 **Greedy Algorithm** – Assigns the nearest available ambulance to each patient  
 **Dynamic Programming (DP)** – Allocates patients to hospitals based on distance & load  
 **Backtracking** – Reallocates patients when hospitals reach capacity  
 **Reallocation Simulation** – Handles real-time updates (new patients, ambulance returns)  
 **Clean Tkinter UI** – Real-time log display and interaction buttons  

---

##  Algorithms Used

| Step | Algorithm | Purpose |
|------|------------|----------|
| **1.** | Greedy | Finds the nearest available ambulance for each patient |
| **2.** | Dynamic Programming | Optimally assigns hospitals considering capacity and load |
| **3.** | Backtracking | Reallocates patients when hospitals are overloaded |

---

##  User Interface

The interface is built using **Tkinter**, designed for simplicity and readability:

-  **Header Section:** Displays the title banner  
-  **Buttons:** “Run Simulation” and “Reallocate Resources”  
-  **Output Console:** Shows real-time log of assignments and updates  
-  **Modern Color Theme:** Light pastels and smooth font styling  

---

## Tech Stack

| Component | Technology |
|------------|-------------|
| **Language** | Python 3 |
| **Framework** | Tkinter |
| **Libraries** | `math`, `random`, `tkinter`, `ttk` |
| **Algorithms** | Greedy, Dynamic Programming, Backtracking |

---

##  How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/MediQuick.git
   cd MediQuick
2. **Run the project**
   python mediquick.py
3. **Use the App**
   Click "▶ Run Simulation" to generate random hospitals, patients, and ambulances
   Click "♻ Reallocate Resources" to simulate updates and new emergencies

##  Folder Structure
MediQuick/
│
├── mediquick.py       # Main Python application
├── README.md          # Documentation
└── assets/            # Optional folder for screenshots or icons
