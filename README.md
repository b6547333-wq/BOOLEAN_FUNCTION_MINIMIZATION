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

F(A,B,C,D)=AB+CD+AD module boolean_function_4var ( input wire A, input wire B, input wire C, input wire D, output wire F ); assign F = (~A & B) | (C & D) | (A & ~D); endmodule /* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:Thiru subramania sami RegisterNumber: 25000201


**RTL realization**

**Output:**
<img width="618" height="836" alt="image" src="https://github.com/user-attachments/assets/bc589bc4-c239-4d25-9dcd-336bccf1b1c5" />

**RTL**
<img width="1080" height="272" alt="image" src="https://github.com/user-attachments/assets/7c069c99-7e44-43f8-b353-9db31087d60b" />

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

