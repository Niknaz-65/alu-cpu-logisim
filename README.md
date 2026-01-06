# 8-bit ALU & Simple CPU (Logisim)

## Overview
Design and implementation of an 8-bit Arithmetic Logic Unit (ALU) and a simple CPU using Logisim-evolution.  
The project demonstrates low-level computing fundamentals including instruction execution, register operations, and control logic.

## Why This Project Matters
- Demonstrates understanding of how software instructions translate into hardware operations
- Builds foundational knowledge relevant to reverse engineering and malware analysis
- Reinforces how CPU-level behavior underpins system execution observed in DFIR and SOC investigations

## Environment
- Platform: Logisim-evolution
- Architecture: Custom 8-bit CPU
- Course Context: Computer Architecture

## Data Collected / Artifacts
- ALU circuit design
- CPU datapath and control logic
- Instruction execution flow
- Status flags and register state changes

## Analysis / Design Steps
1. Designed an 8-bit ALU supporting arithmetic, logical, and shift operations
2. Implemented registers (REG_A, REG_B, REG_OUT)
3. Built a control unit to manage instruction sequencing
4. Integrated datapath and control logic
5. Tested instruction execution using a sample program

## Findings
- ALU operations executed correctly across supported instructions
- Register values and flags updated as expected
- Control unit successfully coordinated instruction flow

## Outcome
- Functional 8-bit CPU capable of executing basic instructions
- Clear demonstration of CPU internals and instruction processing
- Strengthened foundation for low-level system analysis

## Project Files
- `CPU_Project.pdf` — Technical design and analysis report
- `ALU.circ` — Logisim circuit implementation

## Skills Demonstrated
- Computer architecture fundamentals
- Digital logic design
- Instruction execution and control flow
- Low-level system analysis

## Author
**Niknaz Sadehvandi**  
**Cybersecurity Analyst**
