# Verilog HDL Mini-Projects 🚀

A collection of digital design projects ranging from basic logic gates to complex finite state machines (FSMs) and arithmetic circuits. This repository serves as a personal laboratory for exploring hardware description and FPGA-based design.

---

## 📂 Project Categories

### 1. Combinational Logic
* **Basic Gates:** Implementation of AND, OR, XOR, and NOT gates.
* **Multiplexers/Demux:** 2:1, 4:1 Mux and 1:4 Demux.
* **Decoders/Encoders:** 3:8 Decoder and Priority Encoders.
* **Arithmetic Units:** Half Adder, Full Adder, and 4-bit Ripple Carry Adder.

### 2. Sequential Logic
* **Flip-Flops:** SR, D, JK, and T Flip-Flops.
* **Registers:** 4-bit Universal Shift Register.
* **Counters:** 4-bit Synchronous Up/Down Counter, BCD Counter.

### 3. Finite State Machines (FSM)
* **Sequence Detectors:** Moore and Mealy machines for detecting specific patterns (e.g., 1011).
* **Traffic Light Controller:** A simple intersection management system.
* **Vending Machine Logic:** State-based control for item selection and change return.

### 4. Advanced/Arithmetic Systems
* **ALU Design:** A multi-functional Arithmetic Logic Unit performing 8-16 operations.
* **Computer Arithmetic:** Hardware implementation of Booth's Multiplier or Dividers.

---

## 🛠 Tools & Environment

* **Simulation:** Icarus Verilog / ModelSim / Vivado Simulator
* **Synthesis:** Xilinx Vivado / Intel Quartus
* **Waveform Viewing:** GTKWave
* **Language:** Verilog-2001 / SystemVerilog

---

## 🚀 How to Run

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/subhajeet004/verilog-mini-projects.git](https://github.com/subhajeet004/verilog-mini-projects.git)
    ```
2.  **Navigate to a project directory:**
    ```bash
    cd Project_Name
    ```
3.  **Run simulation (example using Icarus Verilog):**
    ```bash
    iverilog -o design_tb.vvp design.v design_tb.v
