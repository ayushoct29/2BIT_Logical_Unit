# 2BIT_Logical_Unit
Performs 7 Logical operation on 2 bit using CMOS. 8x1 Mux for selection of operation on 2 bit and Logical unit optimized to use 11 NAND gate to perform 7 operations
The file attach are of Tanner EDA 
The 8x1 Mux is made using pass transistor logic which uses 7 NMOS and 7 PMOS. It has 3 select line S0,S1 and S2 to select 2 bit logical operation.
Selection Table as follows:
S2  S1  S0    Operation
0   0   0     AND 
0   0   1     NAND
0   1   0     NOR
0   1   1     OR
1   0   0     XNOR 
1   0   1     XOR
1   1   0     NOT(Input 1) 
1   1    1    NOT(Input 2)

Further the Logical unit is optimized to used 11 NAND Gate to perform 7 locial operation.

As a Input you should give Voltage source BIT
Some of the Screen Capture of the design are provided for understanding of the CMOS based Circuit. 

Please provide valuable suggestions and reviews about the project so that i can further improve it.

Thanks 
