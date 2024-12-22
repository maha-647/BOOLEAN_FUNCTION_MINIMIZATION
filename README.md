# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:24000328
RegisterNumber:Mahalakshmimridula.S

module

experiment2(A,B,C,D,f1,w,x,y,z,f2);

inputA,B,C,D,w,x,y,z;

outpur f1,f2;

assing f1=((~B&~D)|(~A&B&~C));

assing f2=((~y&z)|(x&y)|(w&y));

end module



**RTL realization**
![Screenshot (201)](https://github.com/user-attachments/assets/b89868d2-3de8-4a84-89bc-1f502ad99dda)

**Output:**

**RTL**
![Screenshot (202)](https://github.com/user-attachments/assets/4f87772e-2365-48e7-9c5d-b1e357feeaad)

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

