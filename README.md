# BOOLEAN_FUNCTION_MINIMIZATION

**Aim:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime

**Theory:**

**Logic Diagram:**

**Procedure:**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```
Developed by:Gobika k 
RegisterNumber:212222050013

PROGRAM 1:

module expfour(a,b,c,d,f);
input a,b,c,d;
output f;
wire f,f2,f3;
assign f1=(\sim c\&\sim b\&\sim a);
assign f2=(\sim d\&\sim c\&\sim a)
assign f=(c\&\sim(\sim b)\&\sim a);
assign f=f18\sim f28\alpha^{\circ}f3;
endmoudule

PROGRAM 2:

module expfourtwo(a,b,c,d,f);
input f;
wire f1, f2,f3,f4;
assign f1=c\&(\sim b)\&a;
assign f2=d\&(\sim c)\&a;
assign f3=c\&(\sim b)\&a;
assign f4=\sim(f1|f2|f3)
not(f,f4);
endmodule
```

**RTL realization:**
![circuit](https://github.com/Gobikakannan/BOOLEAN_FUNCTION_MINIMIZATION/assets/163496346/3d0b21e3-31f8-48a3-8ee6-fa4bc0f834f0)


**Output:**
![truth table 1](https://github.com/Gobikakannan/BOOLEAN_FUNCTION_MINIMIZATION/assets/163496346/b80727f3-3673-4010-bc92-b04f68c6ab6a)


**Timing Diagram:**
![graph 2](https://github.com/Gobikakannan/BOOLEAN_FUNCTION_MINIMIZATION/assets/163496346/b216b22f-8988-4c6b-bbe3-b8e2cea7ab8e)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

