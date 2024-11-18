****EXP4:FULL ADDER AND SUBTRACTOR****

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


![tt FA1](https://github.com/user-attachments/assets/2ebe1129-72d0-442b-b881-edbf9f52b850)


![tt FB2](https://github.com/user-attachments/assets/0201e242-cef0-49f4-a731-2ff20e514f07)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 


![full adder code](https://github.com/user-attachments/assets/735f24a6-d79c-45b1-8caf-ce3a8aeadb80)


![full subtractoor code](https://github.com/user-attachments/assets/355aba61-977b-4aa2-8995-c041239e8525)



Developed by:Parveen Sulthana RegisterNumber:24900218
*/

**RTL Schematic**


![tt D2](https://github.com/user-attachments/assets/42a11c71-7f7d-4bbb-a971-c8b95be77d17)


![tt D1](https://github.com/user-attachments/assets/2f18f7fc-8dba-4ef2-b726-e79a53b7971c)



**Output Timing Waveform**

![full adder](https://github.com/user-attachments/assets/8c5fedd3-fb08-4bc8-bb5e-fc3b88f70f7e)

![full subtractor](https://github.com/user-attachments/assets/00149b74-746e-49e4-b738-8b8b2bd86ea9)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



