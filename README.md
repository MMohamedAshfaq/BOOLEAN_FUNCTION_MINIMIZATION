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
module boolean(A,B,C,D,F1,w,x,y,z,F2);
input A,B,C,D,w,x,y,z;
output F1,F2;
wire x1,x2,x3,x4,x5,x6;
assign x1=(~B)&(~D);
assign x2=A&B&(~C);
assign x3=(~A)&(B)&(D);
assign x4=(~x)&(z);
assign x5=(x)&(y);
assign x6=(w)&(y);
assign F1=x1|x2|x3;
assign F2=x4|x5|x6;
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

