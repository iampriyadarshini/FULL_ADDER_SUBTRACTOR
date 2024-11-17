### NAME : PRIYADARSHINI K
### REGISTER NUMBER : 24900922
### EXPERIMENT 4 : FULL ADDER AND SUBTRACTOR

## AIM :

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

## EQUIPMENTS REQUIRED :

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

## FULL ADDER AND FULL SUBTRACTER

## FULL ADDER:

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

Figure -1 FULL ADDER

## FULL SUBTRACTOR:

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

## PROCEDURE :
1.Type the program in Quartus software.

2.Compile and run the program.

3.Generate the RTL schematic and save the logic diagram.

4.Create nodes for input and output to generate the timing diagram.

5.For different input combinations generate the timing diagram.

## PROGRAM :
![Screenshot 2024-11-17 111731](https://github.com/user-attachments/assets/a015a2fc-0769-4e65-ae28-4ba41a69dba8)

## TRUTHTABLE :
![TRUTHTABLE4](https://github.com/user-attachments/assets/b09fb3f7-f091-447c-8f2a-2a6005f8c47f)

## RTL OUTPUT :
![RTL OUTPUT 4](https://github.com/user-attachments/assets/3a06f5c5-3283-4f52-854c-c121d2710c1f)

## WAVEFORM OUTPUT :
![WAVEFORM 4](https://github.com/user-attachments/assets/59c02e4c-ee1c-4ef6-b86d-078ee547d239)

## RESULT :
Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



