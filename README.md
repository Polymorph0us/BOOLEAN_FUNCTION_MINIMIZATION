# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule

Developed by:D KEERTHAN 

RegisterNumber:24901007


**RTL**
![image](https://github.com/user-attachments/assets/2e43320b-cedb-497b-ba2e-510ac3b7c39f)

**Timing Diagram**
![image](https://github.com/user-attachments/assets/a4d72a3c-1318-4a3e-8113-dba41ed84897)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

