AIM: To demonstrate the use of bitwise operators and bit manipulation techniques in C++ by performing various bitwise operations such as AND, OR, XOR, NOT, left shift, and right shift on integers, and by allowing the user to set or reset specific bits of a given number.
THEORY:
Bitwise operators in C++ provide a powerful way to manipulate data at the binary level by directly operating on the individual bits of integer values. Unlike arithmetic or logical operators that work with whole numbers or boolean values, bitwise operators treat numbers as sequences of bits (0s and 1s) and perform operations on each corresponding bit pair. The primary bitwise operators include AND (&), OR (|), XOR (^), NOT (~), left shift (<<), and right shift (>>). The AND operator returns 1 for each bit position where both operands have 1s, while the OR operator returns 1 if at least one operand has a 1 in that position. The XOR operator returns 1 only when the bits differ, making it useful for toggling bits. The NOT operator inverts each bit, changing 1s to 0s and vice versa. Shift operators move bits to the left or right, effectively multiplying or dividing the value by powers of two, which can be more efficient than using arithmetic operations. Bitwise operators are commonly used in low-level programming tasks such as setting, clearing, or toggling specific bits in flags or masks, manipulating hardware registers, encoding and decoding data, and optimizing performance-critical code. Mastery of bitwise operations is essential for understanding how data is represented and processed in memory, making them invaluable tools for systems programming, embedded development, and situations requiring fine control over data at the bit level.

ALGORITHM:-
1. Bitwise Operations Program
Start the program.
Initialize two integers a and b.
Perform:
Bitwise AND → a & b
Bitwise OR → a | b
Bitwise XOR → a ^ b
Bitwise NOT of a → ~a
Bitwise NOT of b → ~b
Left Shift a → a << 1
Left Shift b → b << 1
Right Shift a → a >> 1
Right Shift b → b >> 1
Display all results.
End the program.
2. Bit Set and Reset Program
Start the program.
Initialize an integer a.
Prompt the user to enter a bit position to set (turn ON).
Read input and create mask → 1 << position.
Perform a | mask to set the bit.
Prompt the user to enter a bit position to reset (turn OFF).
Read input and create mask → ~(1 << position).
Perform a & mask to reset the bit.
Display updated results.
End the program.

CONCLUSION:-
These programs provide a practical introduction to bitwise operations and manipulation in C++.

The Bitwise Operations Program demonstrates how integers are processed at the binary level using AND, OR, XOR, NOT, and shifts. This is essential for understanding system-level programming and hardware interfacing.
The Bit Set/Reset Program highlights how individual bits can be dynamically controlled using masks. This technique is widely applied in configuring hardware registers, managing permissions, and optimizing storage.
By mastering these concepts, programmers gain fine control over binary data, enabling efficient and optimized low-level programming, especially in areas such as embedded systems, cryptography, and performance-critical software.
