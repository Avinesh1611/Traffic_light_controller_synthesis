# EXP6 : Traffic Light Controller -Synthesize the Gate Level Netlist and tabulate Area and Power reports

## Aim:

Synthesize Traffic Light Controller design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Creating an SDC File

•	In your terminal type “gedit input_constraints.sdc” to create an SDC File if you do not have one.

### Step 3 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

## Synthesis RTL Schematic :

![WhatsApp Image 2024-11-21 at 11 52 49_c6191b12](https://github.com/user-attachments/assets/488f1cb1-b774-4c18-801c-47757a346533)


## Area report:
![WhatsApp Image 2024-11-21 at 11 52 49_0ddf3b2e](https://github.com/user-attachments/assets/0f9ec4a0-bd8f-4e48-bfd4-6233ab4a6b1e)


## Power Report:

![WhatsApp Image 2024-11-21 at 11 52 50_485b7736](https://github.com/user-attachments/assets/9ad0c1e7-bb62-4d0e-a8b6-8b0b37c8730f)


## Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
