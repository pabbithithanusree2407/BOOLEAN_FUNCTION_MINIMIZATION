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

Developed by:pabbithi Thanusree
RegisterNumber:212224050028 
*/
```
module exp2a(a,b,c,d,F1);
input a,b,c,d;
output F1;
assign F1=((~a&b&d)|(~b&~d)|(a&b&~c));
endmodule
```
```
module exp2b(w,x,y,z,F2);
input w,x,y,z;
output F2;
assign F2=((~y&z)|(x&y)|(w&y));
endmodule
```



**RTL realization**

**Output:**
![Exp-2a](https://github.com/user-attachments/assets/4a013201-759b-420d-bdbc-ffef9f0af449)
![image](https://github.com/user-attachments/assets/2196459c-7af7-4ae2-ae96-d69d16361c8b)

**RTL**
![Screenshot 2025-04-07 134934](https://github.com/user-attachments/assets/5e922f59-d47f-4868-bc4f-6168ba25ac88)
![image](https://github.com/user-attachments/assets/9e4d9413-1152-41f1-8701-7d6249b4f08a)

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

