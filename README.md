# EXP4:FULL_ADDER_SUBTRACTOR

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

![tt FA1](https://github.com/user-attachments/assets/608c2590-9725-456e-90ca-8f27c258bafd)

![tt FB2](https://github.com/user-attachments/assets/a1ba4f49-b2cb-47e3-94ba-3a5fac4fdf00)


**Procedure**

Write the detailed procedure here

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.

**Program:**

![full adder code](https://github.com/user-attachments/assets/71a20247-cfb8-4a22-9d12-0271c7d2607a)

![full subtractor code](https://github.com/user-attachments/assets/fe5f6198-236a-4b50-9ba4-2a580cc1ab39)


**RTL Schematic**

![full adder diagram](https://github.com/user-attachments/assets/29bec8c3-8091-4f19-bcb0-ee3427e5a123)

![full subtractor diagram](https://github.com/user-attachments/assets/b0da3861-ee94-4f3a-9184-299054fe4f53)



**Output Timing Waveform**

![full adder waveform](https://github.com/user-attachments/assets/6ba70f4f-48ad-4dc3-8cab-5c07557d052e)

![full subtractor waveform](https://github.com/user-attachments/assets/a0ffe129-bcaa-44d0-b2f8-46dae7337920)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



