# FULL_ADDER_SUBTRACTOR
# NAME.- DEEPIKA G
# REG NO.- 212224040060

Implementation-of-Full-Adder-and-Full-subtractor-circuit

AIM:

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

Equipments Required:

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

Full Adder and Full Subtractor:

Full Adder:

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

Figure -1 FULL ADDER:

Full Subtractor:

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

Truthtable:


![Screenshot 2024-12-12 052352](https://github.com/user-attachments/assets/ed8481c3-8f2f-4f2b-9324-64b01628fc9a)


![Screenshot 2024-12-12 052457](https://github.com/user-attachments/assets/090a0693-12f4-45f3-8400-efd6c8cd0bd5)



Procedure:
1. Open Quartus II and create a new project.
2. Use schematic design entry to draw the full adder circuit. 
3. The circuit consists of XOR, AND, and OR gates. 
4. Compile the design, verify its functionality through simulation. 
5. Implement the design on the target device and program it.

For Full Subtractor

1. Follow the same steps as for the full adder. 
2. Draw the full subtractor circuit using schematic design. 
3. The circuit includes XOR, AND, OR gates to perform subtraction. 
4. Compile, simulate, implement, and program the design similarly to the full adder.



Program:

![Screenshot 2025-04-15 112802](https://github.com/user-attachments/assets/940dc9d5-31bc-4e5f-8b7b-aff782eac179)



/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 
*/

RTL schematic:

![Screenshot 2025-04-15 113710](https://github.com/user-attachments/assets/a8dcc555-96ae-419a-9390-7e8d4faf68c4)



Output Timing Waveform:

![Screenshot 2025-04-15 113608](https://github.com/user-attachments/assets/93ebb728-016d-45af-94b3-d96ba2c86213)


Result:

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.


