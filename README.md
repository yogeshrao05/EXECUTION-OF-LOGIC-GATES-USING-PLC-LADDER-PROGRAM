# EXECUTION-OF-LOGIC-GATES-USING-PLC-LADDER-PROGRAM


 
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

# Basic Logic Gates:
AND Gate:

Function: Outputs HIGH only when all inputs are HIGH.
Ladder Logic: Represented by two or more normally open contacts in series.

OR Gate:

Function: Outputs HIGH when at least one input is HIGH.
Ladder Logic: Represented by two or more normally open contacts in parallel.

NOT Gate:

Function: Outputs the inverse of the input signal.
Ladder Logic: Represented by a normally closed contact.

NAND Gate:

Function: Outputs LOW only when all inputs are HIGH.
Ladder Logic: An AND gate followed by a NOT gate.

NOR Gate:

Function: Outputs LOW when at least one input is HIGH.
Ladder Logic: An OR gate followed by a NOT gate.

XOR Gate:

Function: Outputs HIGH when an odd number of inputs are HIGH.
Ladder Logic: Represented by a combination of AND, OR, and NOT gates.

# Truth Tables:
 AND Gate:
 
 ![andlogic](https://github.com/user-attachments/assets/c1e60185-b72e-42e2-806e-dbbe90ad569d)

OR Gate:

![orlogic](https://github.com/user-attachments/assets/44c1f5b9-d7b6-4da1-b343-e1d3ec44cf49)

NOT Gate:

![not logic](https://github.com/user-attachments/assets/01a053dd-e082-4414-b389-22032aa1ba94)

NAND Gate:

![nandlogic](https://github.com/user-attachments/assets/a011a431-8a83-48c5-8569-ea02a4cbc3b2)

NOR Gate:

![norlogic](https://github.com/user-attachments/assets/e571e579-5afa-4527-b399-e48737f96b9f)

XOR Gate:

![xorlogic](https://github.com/user-attachments/assets/f5c22ef3-1db7-403a-898f-99b16791c8d4)

# Procedure:
Setup the PLC Programming Environment:

Connect the PLC to the computer system and launch the PLC programming software.
Ensure all input and output devices are correctly connected to the PLC’s I/O modules.
Create Ladder Logic Programs:

For each logic gate, create a ladder logic rung that corresponds to the truth table of the gate.
Use normally open (NO) and normally closed (NC) contacts to implement AND, OR, and NOT logic.
For NAND, NOR, and XOR gates, combine the basic gates appropriately in the ladder diagram.
Simulate the Ladder Logic:

Simulate the ladder logic programs in the PLC software.
Toggle the input states and observe the output corresponding to each gate’s truth table.
# Download and Execute:

If available, download the ladder logic program to the PLC and run it.
Verify the outputs by changing the input states using the connected switches and observing the LEDs or output indicators.
Output of Simulation:
For each logic gate, when the inputs are changed according to the truth tables, the corresponding outputs should be observed as follows:
AND Gate: The output LED or indicator should light up only when both inputs are HIGH.
OR Gate: The output should light up when any one or both inputs are HIGH.
NOT Gate: The output should be the inverse of the input state.
NAND Gate: The output should be HIGH except when both inputs are HIGH.
NOR Gate: The output should be HIGH only when both inputs are LOW.
XOR Gate: The output should light up when exactly one input is HIGH.


# SIMULATION RESULTS 

AND Gate:

![and output](https://github.com/user-attachments/assets/bcdfdaf4-f782-4f15-9246-74a746f51459)

OR Gate:

![or output](https://github.com/user-attachments/assets/35307301-fcaf-41cc-a7e7-b230152b32d9)

NAND Gate:

![nand output](https://github.com/user-attachments/assets/adad979e-7ab1-48a4-98f3-919ab8073633)

NOT Gate:

![not output](https://github.com/user-attachments/assets/3b244ac8-0679-447a-8929-38dbe237e90b)

NOR Gate:

![nor gate](https://github.com/user-attachments/assets/a1c7c759-4d60-43df-93a9-700cbf9a9791)

XOR Gate:

![xor output](https://github.com/user-attachments/assets/236d97f4-0514-499a-9098-262980b93211)


# Results:
The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.
