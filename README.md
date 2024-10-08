# FULL_ADDER_SUBTRACTOR

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

FULL ADDER:

![ex4 full adder](https://github.com/user-attachments/assets/ab737c73-64ab-4113-b76f-bb7239eedd42)

FULL SUBTRACTOR:

![ex4 full sub](https://github.com/user-attachments/assets/4bc72019-5f25-4ff6-ad1a-3e6e11373964)

**Program(1A):**

![EX4 PRO 1A](https://github.com/user-attachments/assets/89d900b4-0dd0-4c83-b4bb-2f48201ee51d)

**RTL Schematic(1A)"**

![EX4 RTL 1A](https://github.com/user-attachments/assets/35fd0570-349c-4290-b87c-a660f46ccb9f)

**Output Timing Waveform(1A):**

![EX4 OUTWAVE 1A](https://github.com/user-attachments/assets/1ed19256-4162-4858-85b0-366d7699dd6b)

**Program(1B):**

![EX4 PRO 1B](https://github.com/user-attachments/assets/44f61a9d-9c12-48fc-b7f4-8f29c511c720)

**RTL Schematic(1A)"**

![EX 4 RTL 1B](https://github.com/user-attachments/assets/c301664e-f42d-41ff-8ff0-e2263f84490e)

**Output Timing Waveform(1A):**

![EX4 OUTWAVE 1B](https://github.com/user-attachments/assets/7dc9ff21-0061-4e02-9455-d3813f3b4fa5)

Developed by: M.VIJAY 

RegisterNumber: 24900322
 
**Result:**

  Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



