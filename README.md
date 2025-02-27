# Implementation of Half-Subtractor-and-Full-subtractor
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
Hardware – PCs, Cyclone II , USB flasher, Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure
~~~
STEP 1: Use module project name(input,output) to start the Verilog programmming.
STEP 2: Assign inputs and outputs using the word input and output respectively.
STEP 3: Use defined keywords like wire,assign and required logic gates to represent the boolean
expression.
STEP 4: Use each output to represnt onre for differnce and the other for borrow.
STEP 5: End the verilog program using keyword endmodule.
~~~
## Program:
~~~
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: Vikaash K S
RegisterNumber: 23013426
~~~
## Half subtractor:
![Exp4 hs code](https://github.com/Vikaash19/Experiment--04-Half-Subtractor-and-Full-subtractor/assets/148514589/e0ed339f-3088-49e3-9a03-973697c696d3)

## Full subtractor:
![Exp4 fs code](https://github.com/Vikaash19/Experiment--04-Half-Subtractor-and-Full-subtractor/assets/148514589/98b1c763-b131-43dc-a69b-928450169857)

## Output:
## Truthtable:
## Half subtractor:
![Exp4 truthtable hs](https://github.com/Vikaash19/Experiment--04-Half-Subtractor-and-Full-subtractor/assets/148514589/ad3a3ce7-0f64-417a-b964-458e7b97e1f5)

## Full subtractor:
![Exp4 truthtable fs](https://github.com/Vikaash19/Experiment--04-Half-Subtractor-and-Full-subtractor/assets/148514589/666a24a0-b60e-4b54-ac59-82d8b9e66c82)

##  RTL realization:
## Half subtractor:
![Exp4 hs RTL diagram](https://github.com/Vikaash19/Experiment--04-Half-Subtractor-and-Full-subtractor/assets/148514589/d0c6a758-052b-4f26-81b7-93e96c8e945f)

## Full subtractor:
![Exp4 fs RTL diagram](https://github.com/Vikaash19/Experiment--04-Half-Subtractor-and-Full-subtractor/assets/148514589/dd890d46-d0fd-40a2-a9ab-7eeab18b4e68)

## Timing diagram: 
## Half subtractor:
![hs wave](https://github.com/Vikaash19/Experiment--04-Half-Subtractor-and-Full-subtractor/assets/148514589/28a8b447-971a-4e1a-b5a8-d6a1d81b3f7c)

## Full subtractor:
![fs wave](https://github.com/Vikaash19/Experiment--04-Half-Subtractor-and-Full-subtractor/assets/148514589/38732de1-6440-47b2-b63a-205fd6a59408)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
