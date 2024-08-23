# EX-01 EXECUTION OF LOGIC GATES USING PLC LADDER PROGRAM
### NAME: YOGESH RAO S D
### REG.NO: 212222110055
 
# Aim:
To implement and verify the functioning of basic logic gates (AND, OR, NOT, NAND, NOR, XOR) using a PLC ladder program and simulate the outputs.

# Apparatus Required:
Programmable Logic Controller (PLC) - A PLC with support for ladder logic programming.
PLC Programming Software - Software like RSLogix, TIA Portal, or CX-Programmer.
Computer System - To run the PLC programming software and perform simulations.
Input Devices - Push buttons or switches to simulate inputs (I/O modules).
Output Devices - LEDs or any indicator to visualize the output of logic gates (I/O modules).
Wires and Connectors - For connecting input/output devices to the PLC.
Power Supply - Appropriate power supply for PLC and peripherals.

# Theory:
Logic gates are the fundamental building blocks of digital circuits, and they process binary inputs to produce a binary output. In PLC programming, these logic gates can be implemented using ladder logic, which is a graphical programming language resembling electrical relay logic.

## Basic Logic Gates:
#### AND Gate:</br>
Function: Outputs HIGH only when all inputs are HIGH.</br>
Ladder Logic: Represented by two or more normally open contacts in series.</br>

#### OR Gate:</br>
Function: Outputs HIGH when at least one input is HIGH.</br>
Ladder Logic: Represented by two or more normally open contacts in parallel.</br>

### NOT Gate:</br>
Function: Outputs the inverse of the input signal.</br>
Ladder Logic: Represented by a normally closed contact.</br>

### NAND Gate:</br>
Function: Outputs LOW only when all inputs are HIGH.</br>
Ladder Logic: An AND gate followed by a NOT gate.</br>

### NOR Gate:</br>
Function: Outputs LOW when at least one input is HIGH.</br>
Ladder Logic: An OR gate followed by a NOT gate.</br>

#### XOR Gate:</br>
Function: Outputs HIGH when an odd number of inputs are HIGH.</br>
Ladder Logic: Represented by a combination of AND, OR, and NOT gates.</br>

# Truth Tables:
 
# Procedure:
#### Setup the PLC Programming Environment:
Connect the PLC to the computer system and launch the PLC programming software.
Ensure all input and output devices are correctly connected to the PLC’s I/O modules.

#### Create Ladder Logic Programs:
For each logic gate, create a ladder logic rung that corresponds to the truth table of the gate.
Use normally open (NO) and normally closed (NC) contacts to implement AND, OR, and NOT logic.
For NAND, NOR, and XOR gates, combine the basic gates appropriately in the ladder diagram.

#### Simulate the Ladder Logic:
Simulate the ladder logic programs in the PLC software.
Toggle the input states and observe the output corresponding to each gate’s truth table.

## Download and Execute:
If available, download the ladder logic program to the PLC and run it.</br>
Verify the outputs by changing the input states using the connected switches and observing the LEDs or output indicators.</br>
Output of Simulation:</br>
For each logic gate, when the inputs are changed according to the truth tables, the corresponding outputs should be observed as follows:</br>
AND Gate: The output LED or indicator should light up only when both inputs are HIGH.</br>
OR Gate: The output should light up when any one or both inputs are HIGH.</br>
NOT Gate: The output should be the inverse of the input state.</br>
NAND Gate: The output should be HIGH except when both inputs are HIGH.</br>
NOR Gate: The output should be HIGH only when both inputs are LOW.</br>
XOR Gate: The output should light up when exactly one input is HIGH.</br>

## Procedure:
### Setup the PLC Programming Environment:
Connect the PLC to the computer system and launch the PLC programming software.</br>
Ensure all input and output devices are correctly connected to the PLC’s I/O modules.</br>
Create Ladder Logic Programs:</br>
For each logic gate, create a ladder logic rung that corresponds to the truth table of the gate.</br>
Use normally open (NO) and normally closed (NC) contacts to implement AND, OR, and NOT logic.</br>
For NAND, NOR, and XOR gates, combine the basic gates appropriately in the ladder diagram.</br>
Simulate the Ladder Logic:</br>
Simulate the ladder logic programs in the PLC software.</br>
Toggle the input states and observe the output corresponding to each gate’s truth table.</br>

# SIMULATION RESULTS 
### AND GATE:
<img src="https://github.com/user-attachments/assets/2f6cbcb8-732d-4f57-b88c-6417a8a4f82c" width="500" height="300" />

### OR GATE:
<img src="https://github.com/user-attachments/assets/ba504b79-a173-4f03-b1c1-0303a5b3e03a" width="500" height="300" />

### NOT GATE:
<img src="https://github.com/user-attachments/assets/6732a4b3-b79f-4976-ac04-ec5650af37ec" width="500" height="300" />

### NAND GATE:
<img src="https://github.com/user-attachments/assets/16f56012-8cc7-4107-bca1-02530c986d67" width="500" height="300" />

### NOR GATE:
<img src="https://github.com/user-attachments/assets/6ea8863d-67f8-4bf4-bf8d-4200bac9847d" width="500" height="300" />

## Results:
The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.
