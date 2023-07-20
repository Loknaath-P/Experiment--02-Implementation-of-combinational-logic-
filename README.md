## Name: P.LOKNAATH
## RegisterNumber: 23004546


# Experiment 02 Implementation of combinational logic

 
## AIM:

To implement the given logic function verify its operation in Quartus using Verilog programming.
  ~ F1 = A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D

 
 
 
## Equipments Required:

### Hardware – PCs, Cyclone II , USB flasher
### Software – Quartus prime



## Theory: 

A combinational circuit is a circuit in which the output depends on the present combination of inputs. Combinational circuits are made up of logic gates. The output of each logic gate is determined by its logic function. Combinational circuits can be made using various logic gates, such as AND gates, OR gates, and NOT gates.


### Procedure:
1. Create a New Project:
   - Open Quartus and create a new project by selecting "File" > "New Project Wizard."
   - Follow the wizard's instructions to set up your project, including specifying the project name, location, and target device (FPGA).

2. Create a New Design File:
   - Once the project is created, right-click on the project name in the Project Navigator and select "Add New File."
   - Choose "Verilog HDL File" or "VHDL File," depending on your chosen hardware description language.

3. Write the Combinational Logic Code:
   - Open the newly created Verilog or VHDL file and write the code for your combinational logic.   
     
4. Compile the Project:
   - To compile the project, click on "Processing" > "Start Compilation" in the menu.
   - Quartus will analyze your code, synthesize it into a netlist, and perform optimizations based on your target FPGA device.

5. Analyze and Fix Errors:
   - If there are any errors or warnings during the compilation process, Quartus will display them in the Messages window.
   - Review and fix any issues in your code if necessary.
   - View the RTL Diagram.

6. Verification:
   - Click on "File" > "New" > "Verification/Debugging Files" > "University Program VWF".
   - Once Waveform is created Right Click on the Input/Output Panel > " Insert Node or Bus" > Click on Node Finder > Click On "List" > Select All.
   - Give the Input Combinations according to the Truth Table amd then simulate the Output Waveform.

### Program:

![image](https://github.com/Loknaath-P/Experiment--02-Implementation-of-combinational-logic-/assets/139841683/93896a89-55e4-4907-9346-2d2d32512ab6)

   



### RTL realization

![image](https://github.com/Loknaath-P/Experiment--02-Implementation-of-combinational-logic-/assets/139841683/38bf58bd-360d-4139-8903-ce98981a615c)


### Truth Table

![image](https://github.com/Loknaath-P/Experiment--02-Implementation-of-combinational-logic-/assets/139841683/22b7a74b-d01b-4599-a2e0-d6d8f991f87d)


### Timing Diagram

![image](https://github.com/Loknaath-P/Experiment--02-Implementation-of-combinational-logic-/assets/139841683/e02c6126-6232-4c4a-b3a8-44eda3fa2a1a)



## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
