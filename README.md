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
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: M.MOHAMED ASHFAQ
RegisterNumber:212224240090 */


**RTL realization**
![DE 2 EXP](https://github.com/user-attachments/assets/de50c3de-61f3-40e2-9240-91f5421746b8)

**Output:**
![DE EXP 2](https://github.com/user-attachments/assets/fdec6e57-d2f4-4183-8f5d-ce63630dc1a9)



**Timing Diagram**
![EXP 2 DE](https://github.com/user-attachments/assets/c89d6b92-35e4-449f-89d7-5118ba7a3ecd)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

