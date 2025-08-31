# Parity Generator and Checker

## Project Overview
This project implements a **Parity Generator** and **Parity Checker** using Verilog.  
- **Parity Generator**: Generates an **even parity bit** for a 4-bit input data.  
- **Parity Checker**: Checks the received data along with the parity bit to detect single-bit errors.  

This project demonstrates concepts of **error detection** and **combinational logic** in digital systems.

---

## Features
- 4-bit input data
- Even parity generation
- Single-bit error detection
- Waveform visualization using **GTKWave/EPWave**

---

## File Structure
| File Name               | Description                                      |
|-------------------------|--------------------------------------------------|
| `txt file ` | Verilog module for parity generation & checking and Testbench to simulate the design          
| `png`        | Waveform file generated during simulation      |

---

## How to Run
1. Open **EDA Playground**.
2. Select **SystemVerilog / Icarus Verilog + GTKWave**.
3. Copy **`parity_gen_checker.sv`** in the main code window.
4. Copy **`parity_tb.sv`** in the testbench window.
5. Click **Run** to simulate.
6. Open **`parity.vcd`** in GTKWave/EPWave to view signals:
   - `data[3:0]`: Input data
   - `parity`: Generated parity bit
   - `error`: Parity check result

---

## Console Output Example
| Time | Data  | Parity | Error |
|------|-------|--------|-------|
| 10   | 0000  | 0      | 0     |
| 20   | 0001  | 1      | 0     |
| 30   | 0010  | 1      | 0     |
| 40   | 0011  | 0      | 0     |
| 50   | 0100  | 1      | 0     |
| 60   | 0101  | 0      | 0     |
| 70   | 0110  | 0      | 0     |
| 80   | 0111  | 1      | 0     |
| 90   | 1000  | 1      | 0     |
| 100  | 1001  | 0      | 0     |
| 110  | 1010  | 0      | 0     |
| 120  | 1011  | 1      | 0     |
| 130  | 1100  | 0      | 0     |
| 140  | 1101  | 1      | 0     |
| 150  | 1110  | 1      | 0     |
| 160  | 1111  | 0      | 0     |

---

## Learning Outcomes
- Understanding **even parity generation**.
- Implementing **parity checking logic**.
- Simulating **combinational circuits** in Verilog.
- Visualizing waveforms with **GTKWave/EPWave**.

---

