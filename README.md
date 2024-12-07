# Adder-and-Subtractor-using-Gates

The 4-bit adder and subtractor circuit can perform addition or subtraction depending on a control signal. This control signal, often referred to as the "mode" or "operation" signal, determines whether the circuit functions as an adder or subtractor. When set to addition mode, the circuit computes the sum of two 4-bit binary numbers but can only produce output of maximum 4-bit binary number. In subtraction mode, it calculates the difference between the two numbers by utilizing the concept of two's complement representation with the help of an EX-OR gate to select the mode.

# SCHEMATIC:

![DTE Schematic_page-0001](https://github.com/user-attachments/assets/7ba4fea5-889a-4421-89e2-80b70dae655f)

# INPUTS:

![image](https://github.com/user-attachments/assets/4676b7b8-707f-4773-804f-9357bdf34b11)

Here various switches are used to select the binary input number.
These switches are pulled down using resistors to give the output as low to the basic gates so that they won’t malfunction during the calculation.
It is a common problem that if the output is not grounded the value could either be 1 or 0 which is not proper to provide a correct calculation.

# 7 segment display for INPUTS: 

![image](https://github.com/user-attachments/assets/9f821d81-186c-47c2-9c74-9f2dc22ed685)

Here we have used a common anode 7 segment display and the driver IC 7447 to display the inputs given from the BINARY TO BCD circuits.

# Binary to BCD converter for inputs (A & B):

INPUT FROM A

![image](https://github.com/user-attachments/assets/0d752a3a-2a28-403d-b4f2-93a3558e8689)

INPUT FROM  B

![image](https://github.com/user-attachments/assets/153777cf-ce6f-4dd1-b3be-badc8f172bba)

# Binary to BCD Code Converter:

![image](https://github.com/user-attachments/assets/9ed0707b-a163-456e-ac90-598ef780d829)

# Drawing K-Map for each outputs:

![image](https://github.com/user-attachments/assets/a24a505a-55e5-410e-b7f9-045ef3004d35)

![image](https://github.com/user-attachments/assets/f8c54554-ce33-4163-a89e-737faaa3dd9d)

![image](https://github.com/user-attachments/assets/7882c551-d26c-4271-9ad4-67b117ebcc8a)

![image](https://github.com/user-attachments/assets/61573a52-3707-42ce-b9ac-dd780c85fc51)

![image](https://github.com/user-attachments/assets/1143372c-d930-45bc-a20d-4f2c3d9afac7)

Minimized expression for each output:

W = AB + AC (carry decimal)

X = A’B’

Y = A’B + BC

Z = ABC’ + A’C

E = D  (first bit)

NOTE:
The same is used for the conversion of binary digits to decimal which is getting inputs from the calculator.









