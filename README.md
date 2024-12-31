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

**Theory**

![image](https://github.com/user-attachments/assets/dd4d6cb6-2a98-4646-9e4d-f2f5899a802a)
![image](https://github.com/user-attachments/assets/868ba8ed-b988-480b-a2b3-40446047719d)


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

![image](https://github.com/user-attachments/assets/d4343ad7-784c-4244-bc58-0d03515eee35)


**RTL - F2**

![image](https://github.com/user-attachments/assets/97cd96bf-388c-4360-b17c-571ea57c7eda)


**Timing Diagram - F1**

![image](https://github.com/user-attachments/assets/4ae47c21-c7f4-4901-aff4-b39ab04dd0bc)

**Timing Diagram - F2**

![image](https://github.com/user-attachments/assets/184d97e7-6718-47ca-b358-eb6ac8479524)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

