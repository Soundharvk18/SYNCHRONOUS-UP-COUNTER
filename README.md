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

Developed by: Jeya soundhar P

RegisterNumber:212224040138


module ex2a(a,b,c,d,f1);

input a,b,c,d;

output f1;

assign f1=((~a&b&d)|(~b&~d)|(a&b&~c));

endmodule

module ex2b(w,x,y,z,f2);

input w,x,y,z;

output f2;

assign f2=((~y&z)|(x&y)|(w&y));

endmodule


**RTL realization**

![Screenshot 2025-04-21 190546](https://github.com/user-attachments/assets/f85ea5a2-5cc0-474e-8fb8-422dff5ae141)

![Screenshot 2025-04-21 190553](https://github.com/user-attachments/assets/1d819669-7c42-4b62-9f87-4d3de6d0e3f7)


**Truth table**

![Screenshot 2025-04-21 190512](https://github.com/user-attachments/assets/79f0246d-f1e5-4b5e-8514-419d9a991fdc)

![Screenshot 2025-04-21 190535](https://github.com/user-attachments/assets/e76712ba-59bc-45d1-bd1e-9ceb4a1310cf)



**Timing Diagram**

![Screenshot 2025-04-21 190622](https://github.com/user-attachments/assets/bccba43f-21d7-4092-8711-235598b39175)

![Screenshot 2025-04-21 190635](https://github.com/user-attachments/assets/4e791b71-785f-4d17-bdd6-952111aec792)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

