# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: U KRITHIGA
RegisterNumber:  23006499
*/
Logic symbol & Truthtable
RTL realization
### Code:
![code ha](https://github.com/krithigau/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150319401/997c088a-2fc2-4b75-959c-5e54c415b87e)

![FA CODE](https://github.com/krithigau/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150319401/4cd8884a-3a94-4252-a17d-0b47c50485be)

### RTL
![RTL for ha](https://github.com/krithigau/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150319401/0e56a254-9662-48bd-9d4d-6310980be760)
![RTL FA (2)](https://github.com/krithigau/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150319401/3c677309-2b08-4803-807b-1576569cd2bb)

### TIMING DIAGRAM
![Timing diag ha](https://github.com/krithigau/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150319401/321882bc-8ca4-42eb-93be-848760a90b1f)
![FA TIME LINE](https://github.com/krithigau/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150319401/ac9dd123-d716-4203-b584-a791c682dd9b)

### TRUTH TABLE 
![TT FOR HA](https://github.com/krithigau/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150319401/01feb115-ed98-4b84-abfc-c9e0232e0a89)

![TT FOR FA](https://github.com/krithigau/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150319401/104e555a-def0-4bb4-a451-20b2d6825ed8)
### Result:
Thus the given full adder and half adder are verified using verilog programming.
