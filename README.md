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
![image](https://github.com/user-attachments/assets/355d8a1e-5977-4a13-abe4-783f99ade253)


#### Area report:
![image](https://github.com/user-attachments/assets/199e0cd7-5683-47d6-bb76-0035a404578c)


#### Power Report:
![image](https://github.com/user-attachments/assets/88e9e4fc-2b13-4ac6-99ba-0bb4a9232944)

**####Timing Report:**
![image](https://github.com/user-attachments/assets/09a7370e-bf03-49d8-9e32-5d2a9dce1ddf)

#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
