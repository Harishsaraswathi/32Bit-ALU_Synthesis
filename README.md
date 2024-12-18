# Exp-5:32Bit-ALU_Synthesis

## Aim:

Synthesize 32 Bit ALU design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being
used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

#### Synthesis RTL Schematic :

![WhatsApp Image 2024-11-18 at 22 28 18_cd5759d0](https://github.com/user-attachments/assets/52ab88f4-992b-458f-a50f-83f0d900c017)

#### Area report:

![Screenshot (330)](https://github.com/user-attachments/assets/876f014e-a7ab-4e15-bc05-1601bc65dce5)

#### Power Report:

![Screenshot (329)](https://github.com/user-attachments/assets/afb1f71d-3cbe-4f46-b8c7-a1651179c279)

#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
