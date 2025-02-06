# Half-Adder-Portfolio-Page
The purpose of this repository is to demonstrate my understanding of binary addition and its applications in both theory and practice. To achieve this, I will explain one of the simplest methods for adding two binary numbers: the half adder. A half adder is a fundamental circuit designed to compute the sum and carry of two single-bit binary numbers. It serves as the building block for more complex circuits, such as the full adder and multi-bit adders like the 4-bit adder.

As a brief recap, binary numbers consist only of 0s and 1s, unlike decimal numbers, which use digits from 0 to 9. Because binary has a smaller set of digits, numbers appear to grow in length more quickly compared to decimal. For example, the decimal numbers 0, 1, 2, 3, 4, and 5 are represented in binary as 0, 1, 10, 11, 100, and 101, respectively.
![370110080-4279e31a-8d78-4584-b94f-a06585b8a226](https://github.com/user-attachments/assets/f43ff5b1-e7f9-4a14-88f0-8d71141ea0e1)
Here’s how the half adder works based on the truth table:

When both inputs (A and B) are 0, the sum (S) is 0, and there is no carry (Cout = 0).
When A is 0 and B is 1 (or vice versa), the sum (S) is 1 because 0 + 1 = 1, and there is no carry (Cout = 0).
When both inputs are 1, the sum (S) is 0, but the carry-out (Cout) becomes 1. This happens because in binary, 1 + 1 equals 10, where the rightmost digit (0) is the sum, and the leftmost digit (1) is carried to the next place value.
This demonstrates how the XOR gate produces the sum (S = A ⊕ B), while the AND gate determines the carry (Cout = A • B).
![halfadderdiagram](https://github.com/user-attachments/assets/100941a5-641f-4e1a-a1b4-301f2a734c53)
In the diagram, the half adder (HA) takes two binary inputs, A and B, and produces two outputs: the Sum (S) and the Carry-out (Cout). The Sum represents the result of adding A and B, while Cout is the carry bit that moves to the next place value. The half adder is built using two fundamental logic gates: an XOR gate and an AND gate. The XOR gate calculates the sum, while the AND gate determines the carry value.

