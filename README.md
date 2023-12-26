# Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
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



Write the detailed procedure here 


## Program: Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: LAKSHMI PRIYA V
RegisterNumber: 212223220049 

### CODE:
FULL SUBTRACTOR :
![Exp4 fs code](https://github.com/Lakshmi-v-Priya/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151720706/f3bebf86-9605-469c-a675-785ee25feffe)

HALF SUBTRACTOR :
![Exp4 hs code](https://github.com/Lakshmi-v-Priya/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151720706/04ebe578-d36a-4786-a9ad-919f802fdf74)

### TRUTHTABLE ;
FULL SUBTRACTOR :
![Exp4 truthtable fs](https://github.com/Lakshmi-v-Priya/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151720706/9da39ff1-ac59-4135-94f0-1ad701b26082)

HALF SUBTRACTOR :
![Exp4 truthtable hs](https://github.com/Lakshmi-v-Priya/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151720706/6eb21367-2dab-42fc-8417-fe7546c8c365)

### RTL DIAGRAM :
FULL SUBTRACTOR :
![Exp4 fs RTL diagram](https://github.com/Lakshmi-v-Priya/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151720706/2917f526-4f39-4991-ab9e-52e21d0a1e77)

HALF SUBTRACTOR :
![Exp4 hs RTL diagram](https://github.com/Lakshmi-v-Priya/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151720706/8d3c1445-45a5-4aca-aa19-c4feff1e15ec)

### OUTPUT :
FULL SUBTRACTOR :
![fs wave](https://github.com/Lakshmi-v-Priya/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151720706/2d19120f-6398-4558-8a89-9a8541d99218)

HALF SUBTRACTOR :
![hs wave](https://github.com/Lakshmi-v-Priya/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/151720706/066ac5dd-c604-4207-a817-1370ecb3bfef)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
