# EXECUTION-OF-LOGIC-GATES-USING-PLC-LADDER-PROGRAM


 # NAME : Kowshika.R
 # REGISTER NUMBER : 212224220049
 # DEPARTMENT : IT
 # YEAR : 1

 
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

![WhatsApp Image 2025-03-02 at 10 10 08_e4fb612d](https://github.com/user-attachments/assets/edff5ef7-5f07-4cb2-9689-776d207805a2)

![WhatsApp Image 2025-03-02 at 10 10 09_4a55cbb9](https://github.com/user-attachments/assets/ceb1babc-dc28-4e11-be41-375c80b0c133)

![WhatsApp Image 2025-03-02 at 10 10 09_3dbb913f](https://github.com/user-attachments/assets/83ee9acf-c271-42f5-9bdf-820e5a8c42a8)

![WhatsApp Image 2025-03-02 at 10 10 09_8202c388](https://github.com/user-attachments/assets/db6926c4-ac87-450f-9b47-72994fa236ab)

![WhatsApp Image 2025-03-02 at 10 10 09_b5ab12bd](https://github.com/user-attachments/assets/5de8e6c6-2eff-405e-9bbd-088f9119666a)

NOR Gate

![WhatsApp Image 2025-03-02 at 10 10 10_e65067a7](https://github.com/user-attachments/assets/52b2c6cf-13c3-41fe-b2fa-e82edc02b870)


 
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

AND Gate

![Screenshot 2025-02-21 153838](https://github.com/user-attachments/assets/22edf86b-00d7-441c-9caa-21fee7ac8e19)

![Screenshot 2025-02-21 153856](https://github.com/user-attachments/assets/265c63fa-45eb-40b5-a78a-3d8551bb147a)

![EX 1 (2)](https://github.com/user-attachments/assets/c4ebab4c-cdc2-47bc-86a4-ddf1e8ed5a13)

![EX 1](https://github.com/user-attachments/assets/37ea8df7-3391-4342-b881-2ee2e6045abc)

OR Gate

![Screenshot 2025-02-21 154606](https://github.com/user-attachments/assets/a51c7f82-9162-4a17-b5b1-82228d966452)

![Screenshot 2025-02-21 154536](https://github.com/user-attachments/assets/42e8fbf0-ce2b-441b-b444-c22f74934e40)

![Screenshot 2025-02-21 154510](https://github.com/user-attachments/assets/5054098c-93ca-4c99-9329-bcc29affb09f)

![Screenshot 2025-02-21 154524](https://github.com/user-attachments/assets/dcfc2e87-20d5-4f4e-b435-03697c834199)

XOR Gate

![Screenshot 2025-02-21 155505](https://github.com/user-attachments/assets/8a02836f-c641-41f4-b6df-01ea2b2eaab5)

![Screenshot 2025-02-21 155519](https://github.com/user-attachments/assets/a64730f8-b8af-464e-8ccf-73cec7466449)

![Screenshot 2025-02-21 155533](https://github.com/user-attachments/assets/6b50c549-352e-41ef-b4c4-de462cde51ae)

![Screenshot 2025-02-21 155639](https://github.com/user-attachments/assets/9a9abe88-8a91-4f49-84aa-5a637e8cbce9)

NOR Gate

![Screenshot 2025-02-21 160345](https://github.com/user-attachments/assets/c0472d36-ca4c-4062-84e4-65744917a003)

![Screenshot 2025-02-21 160345](https://github.com/user-attachments/assets/d0a367e5-6a1b-45ac-bc36-4255068074f8)

![Screenshot 2025-02-21 160258](https://github.com/user-attachments/assets/a3f7c306-cdf4-47ae-9aa1-a59006958df8)

![Screenshot 2025-02-21 160328](https://github.com/user-attachments/assets/988b05c5-128e-4cff-adac-3632b89164b7)

NAND Gate

![Screenshot 2025-03-02 103426](https://github.com/user-attachments/assets/a3b528db-fc39-4236-8e14-b61d4bec500d)

![Screenshot 2025-02-21 160535](https://github.com/user-attachments/assets/24196a56-42dd-49dc-a7d8-6ddf777f4434)

![Screenshot 2025-03-02 103443](https://github.com/user-attachments/assets/baa31a94-ea55-4448-84b2-d69741f41ea9)

![Screenshot 2025-02-21 160624](https://github.com/user-attachments/assets/f049bb13-f209-4d6e-87b9-c6e20920f954)

NOT Gate

![Screenshot 2025-03-02 103816](https://github.com/user-attachments/assets/4c5e9108-6ca7-4e9b-b3ab-c47ba067bb0c)

![Screenshot 2025-03-02 103829](https://github.com/user-attachments/assets/94aa70f2-f47f-4dc5-8c87-5555ab1d483d)


#Results:
The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.
