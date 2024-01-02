                           # Experiment--02-
DATE                    Implementation-of-combinational-logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
 
 
## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime


## Theory
 

## Logic Diagram
## Procedure


1. Understand the Binary to Gray Code Conversion:
Familiarize yourself with the conversion table for 4-bit binary to gray code.
2. Design the 4-bit Binary to Gray Code Converter Circuit:
For each bit position, determine the logic gates required to generate the corresponding gray code bit.

Use XOR gates for the bits where the binary and gray code differ.

Connect the output of each XOR gate to the corresponding gray code bit.

3. Implementing the Circuit using Logic Gates:
Utilize basic logic gates such as AND, OR, and XOR gates.

Connect the gates based on the design from step 2.

Ensure proper power supply connections.

4. Verify the Circuit:
Simulate the circuit using a digital logic simulator to ensure the correct conversion from binary to gray code.

Test the circuit with all possible 4-bit binary inputs.

5. Build the Physical Circuit:
Once satisfied with the simulation results, implement the circuit using physical components (ICs, wires, etc.).

Double-check the connections and ensure everything is properly connected.

6. Test the Physical Circuit:
Apply different 4-bit binary inputs to the converter and verify that the outputs match the expected gray code values.
## Program:



![screenshot 2024-01-01 at 21 43 41_8ccb8802](https://github.com/tamilh45/Experiment--02-Implementation-of-combinational-logic-/assets/150312761/e940a987-2496-4aa1-aa1a-3378d9df891d)

/*
Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
Developed by: TAMIL PAVALAN M
RegisterNumber: 212223110058  
*/
## RTL realization

![screenshot 2024-01-01 at 21 44 51_42e6d758](https://github.com/tamilh45/Experiment--02-Implementation-of-combinational-logic-/assets/150312761/52540b3d-77b9-48f3-82de-8032e9b93e2a)


## Output:
## RTL
## Timing Diagram

![screenshot 2024-01-01 at 21 43 41_8ccb8808](https://github.com/tamilh45/Experiment--02-Implementation-of-combinational-logic-/assets/150312761/ad6fcafb-6a32-4924-8791-a5e09bc131da)



## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
