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

Developed by: Prabu Karthiek B
RegisterNumber: 24010663
```
module ex2(a,b,c,d,w,x,y,z,f1,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```


**RTL realization**
![WhatsApp Image 2024-12-02 at 9 02 09 PM](https://github.com/user-attachments/assets/b1bd21bd-718c-43e1-99aa-774769da8b93)



**Timing Diagram**
![WhatsApp Image 2024-12-02 at 9 02 09 PM](https://github.com/user-attachments/assets/968199d9-1166-4508-9cbd-df8504d326f6)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

