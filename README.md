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



**Figure -1 FULL ADDER**
![WhatsApp Image 2025-10-16 at 16 01 37_d45cc9c7](https://github.com/user-attachments/assets/a5f1c75c-d378-4537-8314-da015bde135d)

**Full Subtractor**
![WhatsApp Image 2025-10-16 at 16 01 33_51b04f81](https://github.com/user-attachments/assets/7f599b2d-e1b0-4a50-ba6d-e9d310532cf2)

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.


Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

**Procedure**

Write the detailed procedure here

**Program:**

<img width="1785" height="942" alt="Screenshot 2025-10-16 164601" src="https://github.com/user-attachments/assets/8c9dd576-e7e0-4ae3-8703-319fc1125b10" />

<img width="1846" height="888" alt="Screenshot 2025-10-16 164746" src="https://github.com/user-attachments/assets/dde910dd-7caa-4db4-81cf-6c24a4225ada" />

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by:Ramesh Jaisurya RegisterNumber:25005800
*/

**RTL Schematic**
![WhatsApp Image 2025-10-16 at 16 01 31_35a69e7f](https://github.com/user-attachments/assets/d43048ba-8ff9-4b6d-82f4-05825a1801c3)
![WhatsApp Image 2025-10-16 at 16 01 31_d1310bac](https://github.com/user-attachments/assets/3e800394-9295-4a1c-936f-e4b73b6001a4)

**Output Timing Waveform**

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



