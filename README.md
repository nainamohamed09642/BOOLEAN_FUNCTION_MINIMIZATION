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
module combinationalcircuit(A,B,C,D,F1);
input A,B,C,D;
output F1;
wire x1,x2,x3,x4,x5;
assign x1=(~A)&(~B)&(~C)&(~D);
assign x2=(A)&(~C)&(~D);
assign x3=(~B)&(C)&(~D);
assign x4=(~A)&(B)&(C)&(D);
assign x5=(B)&(~C)&(D);
assign F1=x1|x2|x3|x4|x5;
endmodule
Developed by:NAINA MOHAMED Z
RegisterNumber:*/212223230131

**RTL realization**
![Screenshot 2024-03-12 141031](https://github.com/nainamohamed09642/BOOLEAN_FUNCTION_MINIMIZATION/assets/151916360/8387f582-2a43-4fb9-8e94-95011138e5cb)

**Output:**
![Screenshot 2024-03-12 141042](https://github.com/nainamohamed09642/BOOLEAN_FUNCTION_MINIMIZATION/assets/151916360/592bd9ac-c5af-427d-8bc8-660d1db57c20)

**Timing Diagram**
![Screenshot 2024-03-12 141058](https://github.com/nainamohamed09642/BOOLEAN_FUNCTION_MINIMIZATION/assets/151916360/ccfd3061-6f80-4b23-9260-15b863efe862)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

