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
<img width="399" height="343" alt="image" src="https://github.com/user-attachments/assets/2018327c-e5c4-4703-b009-7cd68a324237" />


**Truthtable**
<img width="455" height="475" alt="image" src="https://github.com/user-attachments/assets/c0da1847-e7f4-4633-a873-43e3550a33ee" />


**Procedure**

Type the program in Quartus software.

Compile and run the program.

Generate the RTL schematic and save the logic diagram.

Create nodes for inputs and outputs to generate the timing diagram.

For different input combinations generate the timing diagram.

**Program:**
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/532e0026-0d35-43a7-a835-126d3ac728c2" />


/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/

**RTL Schematic**
RTL Schematic Full Adder Logic Diagram: 
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e3604694-1f58-4a08-99b0-aff242f8be46" />

Full Subtractor Logic Diagram: 
<img width="1280" height="680" alt="image" src="https://github.com/user-attachments/assets/fa8339f0-eb35-419f-ae57-72e96d68b626" />

**Output Timing Waveform**
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/677490f4-97aa-4d67-ad04-0f2146bec1d4" />

Full Subtractor Waveform:
<img width="1280" height="680" alt="image" src="https://github.com/user-attachments/assets/21cf0080-fcc1-4649-9259-17a610655f31" />

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



