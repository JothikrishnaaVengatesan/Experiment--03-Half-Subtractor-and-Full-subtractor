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


## Program:
/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: JOTHIKRISHNAA V
RegisterNumber:  212223100017
*/

## Code:
## Half Subtractor
![program](https://github.com/JothikrishnaaVengatesan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148514555/da3509a2-f69a-4074-b486-bd7b00452c1d)

## Full Subtractor
![program](https://github.com/JothikrishnaaVengatesan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148514555/efe71f25-fe9c-4be1-b0a9-a59bb1fc8ca2)

## Truthtable
## Half Subtractor
![truth table](https://github.com/JothikrishnaaVengatesan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148514555/9ed7b3ac-ea6c-48ff-8d04-04bd2e15c65c)

## Full Subtractor
![truth table](https://github.com/JothikrishnaaVengatesan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148514555/75487f20-ddc6-47a0-8047-e9756e0148f6)

##  RTL realization
## Half Subtractor
![RTL viewer](https://github.com/JothikrishnaaVengatesan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148514555/971c8703-28dd-47d1-85a4-c2a630b2cb1a)

## Full Subtractor
![RTL viewer](https://github.com/JothikrishnaaVengatesan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148514555/229284b4-ab12-4323-a678-86c65beb8c14)

## Timing diagram 
## Half Subractor
![Timing diagram](https://github.com/JothikrishnaaVengatesan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148514555/6d562269-5b76-4360-80d6-93aa163905c4)
## full Subtractor
![Timing diagram](https://github.com/JothikrishnaaVengatesan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148514555/58229324-9c10-49a2-9760-2957dccdda9e)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
