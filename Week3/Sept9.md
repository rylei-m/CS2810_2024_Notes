# CS2810 Notes 09/09/2024

## TODO
- Assn 2 - Due Friday
- Quiz 2 - Due Wednesday
- Exam 1 in 2,5 Weeks
  - Thurs Sept 26th - Sat Sept 28th

Last Class Addition

## ALU and Floating-Point
Computer Systems Functions
- CPU Communicating with memory and exchanging memory to perform calcs

### ALU
#### Computational Centerpiece of a Computer
##### The Powerhouse of the CPU
- Takes Two Inputs
- Single Attribute (Num of Data Bits)
- Computes Some Function on Two Inputs

#### ALU Functions
##### Standardized Across MIPS Computers
- If OP == 000: Out = A AND B
- If OP == 001: Out = A OR B
- If OP == 010: Out = A + B
- If OP == 011: Out = INVALID


- If OP == 100: Out = A AND !B
- If OP == 101: Out = A OR !B
- If OP == 110: Out = A - B
- If OP == 111: Out = A < B
  - 0 if A !< B (false); 1 if A < B (true)

## Logisim Binary to Decimal Number
Radix -> Signed Decimal