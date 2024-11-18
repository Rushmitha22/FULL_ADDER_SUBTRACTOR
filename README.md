# EXP 4 : FULL ADDER AND SUBTRACTOR
## NAME : RUSHMITHA R
## REGISTRATION NUMBER : 24006587

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

FULL ADDER :
![FULL ADD TT](https://github.com/user-attachments/assets/ac8a0751-af07-4363-beff-13837394efa9)

FULL SUBTRACTOR :
![FULL SUB TT](https://github.com/user-attachments/assets/fccd8ff1-d0e0-4b71-8a0c-297137679a06)

**Code**

FULL ADDER :
![full adder code](https://github.com/user-attachments/assets/43cd99d6-0de3-4af1-abab-634ee550efb2)


FULL SUBTRACTOR:
![full subtractor code](https://github.com/user-attachments/assets/b31d68c8-7073-4298-8b33-893da1480d85)


**Procedure**

1. Type the program in Quartus software.
2. Compile and run the program.
3. Generate the RTL schematic and save the logic diagram.
4. Create nodes for inputs and outputs to generate the timing diagram.
5. For different input combinations generate the timing diagram

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:24006587
*/

**RTL Schematic**

FULL ADDER :
![full adder logic](https://github.com/user-attachments/assets/0f9ce3ba-ead0-49d1-a521-ebabda84d43b)

FULL SUBTRACTOR :
![full subtractor logic dia](https://github.com/user-attachments/assets/be99c723-96fa-43a5-aca5-d1dff3732e99)

**Output Timing Waveform**

FULL ADDER :
![full adder waveform](https://github.com/user-attachments/assets/7ef2a250-c518-46a2-b635-9126a2700c1e)

FULL SUBTRACTOR:
![Full subtractor waveform](https://github.com/user-attachments/assets/363022a9-06bb-4882-be92-f17c6b13d27e)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



