# CS2810 08/28/2024
## Boolean Laws, Logic Gates, NAND Gates

### Boolean Laws
All Computers and be Built with And, Or, and Not Operations
Each Operation is implemented with physical hardware
More Simplified Operations = Lower cost + More Efficient System

A*1=A \
- if A=0 the Output with be False
- if A=1 the Output will be True
#### Name, And Form, Or Form
- Identity Law, 1*A=A, 0+A=A
- Zero's and One's Law, 0+A=0, 1+A=1
- Inverse Law, A*!A=0, A+!A=1
- Commutative Law, A*B=B*A, A+B=B+A
- Associative Law, A*(B*C)=(A*B)*C, A+(B+C)=(A+B)+C
- De Morgen's Law, !(A*B)=!A+!B, !(A+C)=!A*!C
    - A = It is Raining
    - B = It is Cold
    - !(A+B) = Not Raining or Cold
      - It is not true that it is raining or cold
      - Essentially = it is Not Raining And it is Not Cold
    - Invert the Terms and Flip the Sign
##### Example:
(A+B)+(!B+!A) \
(A+B+!B+!A) Associative Law \
(A+!A+B+!B) Commutative Law \
(A+!A)+(B+!B) Inverse Law \
1+1 Simplify \
1 \

### Logic Gates
#### The Physical Implementation of Boolean Algebra
Building Blocks for Modern Computers

XOR Gate
- True if only one input is true but not both

NOR Gate
- The inverse of whatever an OR gate outputs

NAND Gate
- If both inputs are 1 the output is 0
- If both inputs are 0 the output is 1

XNOR Gate
- Exclusive True if both inputs are the same

### Truth Table to Boolean Expression
- Only Focus on the Rows with an Output of 1
- Convert Each Row to a Series of ANDS/NOTS
- Combine Each Expression with an OR

### The Expressive Power of NAND (Universal Gate)
- Not(x)=xNANDx
- xANDy= !(xNANDy)
- xORy = !(!(xORy))
  - !(!(x+y)) = NOT(NOT(x)AND NOT(y))
- NOT, AND, OR - Can Be Realized Using NAND

### Assignment 1
Given a Single NAND Gate, Build Every other Logic Gate
