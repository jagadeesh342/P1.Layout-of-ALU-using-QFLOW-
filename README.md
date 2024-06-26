#  Layout Of ALU using QFLOW 
![pro](https://github.com/jagadeesh342/P1.Layout-of-ALU-using-QFLOW-/blob/main/Layout%20of%20ALU%20in%20MAGIC.png)
 
## Description:
This project aims to design and implement the layout of an Arithmetic Logic Unit (ALU) using Qflow, an open-source digital synthesis flow based on open-source tools. The ALU is a fundamental component of many digital systems, performing arithmetic and logical operations on binary numbers. By leveraging Qflow, the project explores the process of RTL to GDSII (Register Transfer Level to Graphic Data System II) synthesis, including synthesis, placement, routing, and layout. Through this project, the aim is to gain insights into digital design methodologies, physical design automation, and the practical aspects of implementing complex digital circuits.





## Tools and Technologies:-  

## Verilog
- Iverilog (verilog file compiler)
- GTKWave (for viewing waveforms)
  
## Qflow
- Yosys (for synthesis)
- Graywolf (for placement)
- QRouter (for routing)
- Magic (for layout visualization)





## Key Objectives:

- Design RTL description of the ALU functionality.
- Verify the  functionality of the ALU layout through simulation
- Synthesize the RTL code using Qflow synthesis tool Yosys.
- Perform floorplanning, placement and routing to generate the physical layout.
- Optimize the layout for performance, area and power.








# Approach 

# 1.Verilog 
  Hardware description language for RTL design
 ### Iverilog :
Simulates and verifies digital circuits.
 ### Gtkwave : 
 Waveform viewer visualizes simulation results.
 ![pro](https://github.com/jagadeesh342/P1.Layout-of-ALU-using-QFLOW-/blob/main/Simulation%20using%20GTKWAVE.png)

 
 # 2.Qflow 
  Open-source digital synthesis flow
 ### Yosys : 
RTL synthesis tool converts Verilog to gate-level netlists.
![pro](https://github.com/jagadeesh342/P1.Layout-of-ALU-using-QFLOW-/blob/main/ALU%20synthesis%20using%20YOSYS.png)
### Graywolf : 
Placement tool arranges cells in a chip layout.
![pro](https://github.com/jagadeesh342/P1.Layout-of-ALU-using-QFLOW-/blob/main/Placement.png)
### Qrouter :
Detail router routes connections between cells.
![pro](https://github.com/jagadeesh342/P1.Layout-of-ALU-using-QFLOW-/blob/main/Routing.png)
### Magic : 
VLSI layout tool for chip design.
![pro](https://github.com/jagadeesh342/P1.Layout-of-ALU-using-QFLOW-/blob/main/Layouts%20of%20ALU.jpg)


# Summary 

Successfully we created a layout for the ALU that meets specified performance metrics and design constraints. 

