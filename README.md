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
![WhatsApp Image 2025-10-16 at 16 01 37_7173fa3f](https://github.com/user-attachments/assets/b73b0136-e111-4087-9b34-83e6fa710ee4)

**Full Subtractor**
![WhatsApp Image 2025-10-16 at 16 01 33_e932b33d](https://github.com/user-attachments/assets/6747bef0-2af5-425b-94cf-94f7e2e2648e)

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.


Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

**Procedure**

Write the detailed procedure here

**Program:**
<img width="1785" height="942" alt="Screenshot 2025-10-16 164601" src="https://github.com/user-attachments/assets/f03e9733-80b3-4ec5-965b-2d26f007f48c" />
<img width="1846" height="888" alt="Screenshot 2025-10-16 164746" src="https://github.com/user-attachments/assets/fa40d6da-b5f1-4ebc-b598-950e89436c33" />

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by:Ramesh Jaisurya RegisterNumber:25005800
*/

**RTL Schematic**
![WhatsApp Image 2025-10-16 at 16 01 31_92e030b7](https://github.com/user-attachments/assets/9a0de509-2e23-4a30-8feb-b15585657ce2)
![WhatsApp Image 2025-10-16 at 16 01 31_906f7172](https://github.com/user-attachments/assets/f38f03db-dd6f-4004-8059-922aef8c80c3)

**Output Timing Waveform**

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



