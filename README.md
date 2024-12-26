# BOOLEAN_FUNCTION_MINIMIZATION

DATE:19/11/2024

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1=((~b & ~d)|(~a & b & d)|(a & b & ~c))

F2=((~y & z)|( w & y )|(x & y))

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


  
**Output:**

**RTL**



**Program F1:**

Developed by: Mohammad suhael




RegisterNumber: 24007235




```
module logic2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
```



**RTL realization**
![Screenshot 2024-11-12 102822](https://github.com/user-attachments/assets/14cc4217-9a75-4153-9059-768b9c94316b)


**Timing Diagram**
![Screenshot 2024-11-12 103612](https://github.com/user-attachments/assets/75a0c9e1-f85a-4985-9058-2165381dbde7)


**Program F2:**

```
module logic3(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
```

**RTL realization**
![Screenshot 2024-11-12 104828](https://github.com/user-attachments/assets/858ed8a6-c9e8-4e13-995e-e7109f5cc1a8)






**Timing Diagram**
![Screenshot 2024-11-12 104704](https://github.com/user-attachments/assets/64b6b60e-7a32-41ef-ace6-d47bb88428d4)





**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

