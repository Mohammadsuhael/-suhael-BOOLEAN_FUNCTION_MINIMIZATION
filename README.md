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
```
module logic2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
```

 RegisterNumber: 24007235


**RTL realization**
![Screenshot 2024-11-12 102822](https://github.com/user-attachments/assets/14cc4217-9a75-4153-9059-768b9c94316b)

**Output:**

**RTL**

**Timing Diagram**
![Screenshot 2024-11-12 103612](https://github.com/user-attachments/assets/75a0c9e1-f85a-4985-9058-2165381dbde7)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

