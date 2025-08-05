# AND Logic Gate – Cadence Mini Project (45nm)

##  Overview
This project implements a **2-input AND logic gate** in **Cadence Virtuoso** using the **45nm technology node**.  
The complete flow is covered from **schematic design** to **layout**, including **symbol creation**, **transient analysis**, and **DRC/LVS verification**.

## Tools Used
- **Cadence Virtuoso** – Schematic, Symbol, and Layout Design
- **Spectre Simulator** – Transient analysis
- **Assura/Calibre** – DRC & LVS verification

---

## Project Flow

### 1️. Schematic Design
- Designed a **2-input CMOS AND gate** using **PMOS** and **NMOS** transistors.
- Connected the transistors in series/parallel according to CMOS AND logic implementation.
- Verified circuit connectivity.

### 2️. Symbol Creation
- Created a symbol for the AND gate to use it as a block in higher-level designs.
- The symbol has **two inputs (A, B)** and **one output (Y)**.

### 3️.Transient Analysis
- Simulated the AND gate using the **Spectre Simulator**.
- Applied different combinations of logic inputs and observed the output waveform.
- Verified correct logical operation: Output is HIGH only when both inputs are HIGH.

### 4️. Layout Design
- Created the physical layout of the AND gate according to **45nm design rules**.
- Used **poly**, **metal layers**, **diffusion**, and **contacts** according to PDK guidelines.
- Performed **DRC** to ensure design rule compliance.
- Performed **LVS** to match layout with schematic.

## Results
- **DRC Status:**  Passed (No design rule violations)
- **LVS Status:**  Matched (Layout matches schematic)
- **Functionality:** Verified correct AND gate behavior in simulation.

## Conclusion
- Successfully designed a **2-input AND gate** in **Cadence Virtuoso (180nm)**.
- Verified the design through **schematic simulation**, **layout verification**, and **waveform analysis**.
- The project demonstrates the **full custom VLSI design flow** for a basic logic gate.

## 👩‍💻 Author
- **Name:** Ahana Dwivedi
- **College:** SRMCEM
- **Project Type:** Mini Project – VLSI Design 
