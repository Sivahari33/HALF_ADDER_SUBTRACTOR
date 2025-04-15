NAME:sivaharibalan.k
R.NO:212224220103
DEPT:IT


# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![ex3 DE](https://github.com/user-attachments/assets/3045ae6d-d993-4509-818b-6968a8643d4e)


Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B
![image](https://github.com/user-attachments/assets/f8822f43-880d-4f7b-a705-a34f293eabfd)


Figure -02 HALF Subtractor

**Truthtable**
HALF ADDER:
![WhatsApp Image 2025-04-15 at 11 50 16_68d9aacf](https://github.com/user-attachments/assets/65b2b71d-6e42-4c1d-a62b-bb07a78833f9)
HALF SUBRACTOR:
![image](https://github.com/user-attachments/assets/3448fc31-7c0a-4502-82c3-f09d67d3e432)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
HALF ADDER:
![image](https://github.com/user-attachments/assets/b97eac46-54e5-4b82-8035-a0e8fd5bdc9f)

HALF SUBRACTOR:
![image](https://github.com/user-attachments/assets/2d7f4b45-598e-4bcd-93df-b0c496db842c)

**Output/TIMING Waveform**
HALF ADDER:
![ex3](https://github.com/user-attachments/assets/120aad27-d243-4aa5-8259-e4a5ddb6ac4d)

HALF SUBRACTOR:
![image](https://github.com/user-attachments/assets/96e5be1f-3966-4e4d-961d-f883caecc9db)




**Result:**
To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming has been executed successfully.
