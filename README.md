# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

  = B'D'+ABC'+A'BD

F2=xy’z+x’y’z+w’xy+wx’y+wxy

  =y'z+wy+xy

**Equipment Required:**

Hardware – PCs, Cyclone V , USB flasher

**Software – Quartus prime**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

***F1***
```
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
```
***F2***
```
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
```

Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: D KEERTHAN

RegisterNumber: 24901007 


**RTL - F1**

![image](https://github.com/user-attachments/assets/705be7cd-7476-4f61-8e11-8d28a1ace294)

**RTL - F2**

![image](https://github.com/user-attachments/assets/c1327611-725f-4c4d-aedf-650f36540b48)


**Timing Diagram - F1**

![image](https://github.com/user-attachments/assets/1b540cb4-db68-4a8e-9324-f2eaaf79893d)
**Timing Diagram - F2**

![image](https://github.com/user-attachments/assets/7d2483b8-8016-48e3-9754-c72aaef4c60b)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

