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

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming.*/
```
module boolean_function_4var (
    input  wire A,
    input  wire B,
    input  wire C,
    input  wire D,
    output wire F
);

assign F = (~A & B) | (C & D) | (A & ~D);

endmodule
```

Developed by: HITHESH RAJ R K 
Register Number: 25016560


**RTL realization**

**Output:**

**RTL**
<img width="981" height="596" alt="Screenshot 2025-11-19 135850" src="https://github.com/user-attachments/assets/23e78f0a-1cde-46d0-b70e-0e84bc7535c5" />

**Timing Diagram**
<img width="1069" height="824" alt="Screenshot 2025-11-19 135927" src="https://github.com/user-attachments/assets/8ad268f0-5a03-494a-a200-c26e80abd1c8" />

**Result:**
Thus the given logic functions are implemented using Quartus and their operations are verified using Verilog programming.

