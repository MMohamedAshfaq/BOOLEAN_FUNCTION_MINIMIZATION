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
![Exp 2](https://github.com/user-attachments/assets/c41bb677-4a23-4988-a7a4-70f79a0986e6)

**Output:**
![2ex](https://github.com/user-attachments/assets/a4ae0071-238e-4a2b-b303-fed63343f7f9)




**Timing Diagram**
![exp2](https://github.com/user-attachments/assets/9f1ec447-45e0-48cb-bacb-176b9d6f5e8d)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

