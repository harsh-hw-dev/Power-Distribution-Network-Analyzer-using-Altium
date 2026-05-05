# ⚡ PDN-Insight: Basic PDN Analysis using Altium

## 📌 Overview
This project demonstrates basic Power Distribution Network (PDN) analysis using Altium Designer. It evaluates voltage drop and current distribution across multiple loads connected to a 12V power rail.

---

## 🧠 Objective
- Analyze voltage drop across PDN  
- Study current distribution in parallel loads  
- Understand power integrity fundamentals  
- Validate PDN behavior using simulation  

---

## 🖼️ Project Preview

### 🔹 Schematic
![Schematic](docs/images/schematic.png)

### 🔹 PDN Analyzer Setup
![PDN Analyzer](docs/images/pdn_setup.png)

### 🔹 Simulation Results
![Results](docs/images/results.png)

---

## ⚙️ Design Details

| Parameter        | Value        |
|-----------------|-------------|
| Input Voltage   | 12V         |
| Loads           | 3 × 12Ω     |
| Total Current   | ~2.994A     |
| Load Voltage    | ~11.98V     |
| Voltage Drop    | ~20mV       |

---

## 📊 Key Observations

- Equal loads → uniform current distribution (~1A each)  
- Minimal voltage drop → low PDN impedance  
- Stable power delivery across loads  
- Validates basic Ohm’s Law in PDN  

---

## 🧪 Tools Used
- Altium Designer  
- PDN Analyzer (CST)  

---

## 🚀 How to Run

1. Open project in Altium Designer  
2. Launch **PDN Analyzer**  
3. Select `12V_line`  
4. Run simulation  
5. Analyze voltage & current  

---

## 📂 Repository Structure
PDN-Insight/
│── Schematic.SchDoc
│── PCB.PcbDoc
│── docs/
│ └── images/
│ ├── schematic.png
│ ├── pdn_setup.png
│ └── results.png
│── README.md
---

## 💡 Future Improvements
- Add decoupling capacitors  
- Perform impedance vs frequency analysis  
- Implement target impedance design  
- Compare good vs poor PDN  

---

## 👨‍💻 Author
Harsh Saini
Hardware Design Engineer 
Open To Work
