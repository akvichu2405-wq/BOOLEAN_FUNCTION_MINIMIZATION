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
<img width="728" height="1079" alt="Screenshot 2025-10-07 230706" src="https://github.com/user-attachments/assets/2336df20-2292-47b1-a1ec-e6ba55be2f6d" />


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
Developed by:Vishnu priya A K
RegisterNumber:25018523

module exp2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule 



**RTL realization**
<img width="859" height="649" alt="Screenshot 2025-10-07 210001" src="https://github.com/user-attachments/assets/90b6e5ff-79c3-48a2-92fa-c3b27962f885" />

**Output:**

**RTL**
<img width="1892" height="623" alt="Screenshot 2025-10-07 205844" src="https://github.com/user-attachments/assets/246bb6da-d756-4b68-ac57-fb89f575d009" />

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

