# 32Bit-ALU_Synthesis

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
![WhatsApp Image 2024-11-23 at 23 02 44_4fa1ae34](https://github.com/user-attachments/assets/c5b41676-9587-4c07-86ec-5c26f1462325)

#### Area report:
![WhatsApp Image 2024-11-23 at 23 02 43_932a4e37](https://github.com/user-attachments/assets/e1cfe574-e032-4ac9-8523-570a47834735)

#### Power Report:
![WhatsApp Image 2024-11-23 at 23 02 43_667b1765](https://github.com/user-attachments/assets/3ad9f234-433b-4796-a42f-8a18cdcab22f)

#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
