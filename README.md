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
Developed by: MANISHA SELVAKUMARI S S
RegisterNumber: 23012275 
*/
Code:
![halfadder code](https://github.com/MANISHA21SS/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474298/3a1690cd-5f22-4b7b-b342-d00b6d097f43)
![fulladder code](https://github.com/MANISHA21SS/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474298/0b0c5bc0-448f-44d4-bbde-ca43d0c91633)


### Output:
Half adder:
![halfadder output](https://github.com/MANISHA21SS/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474298/31d4816e-2a43-4720-949a-e87f78cb41a1)
Full adder:
![fulladder output](https://github.com/MANISHA21SS/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474298/e042d4c3-f5bd-4386-8773-e1c3995ccfcc)

### RTL
Half adder:
![halfadder rtl diagram](https://github.com/MANISHA21SS/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474298/9580cc8f-7795-479a-b2a9-059f7b505be3)
Full adder:
![fulladder rtl diagram](https://github.com/MANISHA21SS/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474298/1c386898-a910-4415-ba15-c728f6451581)

### TIMING DIAGRAM
![half adder timing diagram](https://github.com/MANISHA21SS/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474298/b7b46f4c-d0f3-414c-be85-865230301d9a)
![full adder timing diagram](https://github.com/MANISHA21SS/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474298/3ca0b3b0-c9f7-4a47-b2ce-35759a3264ba)



### TRUTH TABLE 
![half adder truthtable](https://github.com/MANISHA21SS/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474298/c929d1cd-6fab-4c19-9dd5-2a2f84eb5787)
![fulladder truthtable](https://github.com/MANISHA21SS/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474298/5085d5d5-13f8-47c7-808c-c1962f6243c0)


### Result:
Thus the half adder and full adder circuits are designed and the truth table is verified using quartus software.
