# EXECUTION-OF-LOGIC-GATES-USING-PLC-LADDER-PROGRAM


 # NAME :Kamali E
 # REGISTER NUMBER :212222110015
 # DEPARTMENT : cse iot
 # YEAR : 3
 # Date: 23.08.2024 
 
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

![image](https://github.com/user-attachments/assets/f5ca2c25-a785-4f61-83c3-2b8c6a5dd6de)

OR Gate:

![image](https://github.com/user-attachments/assets/a4a319ed-b3dd-44da-bc43-93000a52b9e6)


NOT Gate:

![image](https://github.com/user-attachments/assets/b4fd7d35-5d81-4e4f-9fda-6bc8ef6acf0f)


NAND Gate:

![image](https://github.com/user-attachments/assets/652856a7-0ef2-4ca5-8472-48b9f7a4572c)


NOR Gate:

![image](https://github.com/user-attachments/assets/4483c48b-5814-41d2-97e2-99a116ac5c54)

XOR Gate:

![image](https://github.com/user-attachments/assets/fe825ede-bf08-4cf7-a19f-a3070c190bd7)

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

![image](https://github.com/user-attachments/assets/dbe4a61e-c96e-4533-9ede-0108ce4bcf34)

![image](https://github.com/user-attachments/assets/47410d00-aa4c-408e-ab35-c9c0dc64a707)

![image](https://github.com/user-attachments/assets/3359511c-1ac8-4f27-9fcc-880affc3f76e)

![image](https://github.com/user-attachments/assets/9f423530-eb03-408c-8e69-166edb6d7cbd)

![image](https://github.com/user-attachments/assets/805a9579-7953-4d7c-9418-28b7c4eccbcb)

# Results:
The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.
