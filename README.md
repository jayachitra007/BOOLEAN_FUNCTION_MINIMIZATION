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

module exe_2(f_and, f_or, f_not, f_nor, f_nand, f_xor, f_xnor,a,b);
input a,b;
output f_and, f_or, f_not, f_nor, f_nand, f_xor, f_xnor;
and(f_and, a,b);
or(f_or,a,b);
not(f_not,a);
nand(f_nand, a,b);
nor (f_nor, a,b);
xor(f_xor,a,b);
xnor(f_xnor,a,b);
endmodule

Developed by:jayachitra.j RegisterNumber:24900897


**RTL realization**

**Output:**

**RTL**
![image](https://github.com/user-attachments/assets/f1ab46f8-c456-48ab-a229-9b4ce1b8b824)


**Timing Diagram**
![image](https://github.com/user-attachments/assets/7fd3eda5-8ba2-4965-abef-813fd5b17b58)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

