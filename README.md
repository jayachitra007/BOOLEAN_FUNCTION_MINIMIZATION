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


Developed by: jayachitra . J  RegisterNumber:24900897


**RTL realization**


**Output:**

**RTL**
![image](https://github.com/user-attachments/assets/16a451d4-f93b-40db-af6e-21825716fd59)


**Timing Diagram**
![image](https://github.com/user-attachments/assets/4c6181d4-a49d-4302-9732-271a7fb30947)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

