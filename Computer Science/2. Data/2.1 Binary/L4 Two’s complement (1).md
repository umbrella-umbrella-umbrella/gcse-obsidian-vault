# L4 Two’s complement (1)

**Pearson Edexcel GCSE Computer Science (1CP2) — specification 2.1.2.**

> Notes converted from the lesson slides listed below. They are grouped under the matching specification section.

## L4 Two’s complement (1)

### Two’s complement (1)

Learning objectives
In this lesson you will learn to:
- differentiate between signed and unsigned integers
- describe how positive and negative numbers are represented
in two's complement
- find the two's complement of a signed binary number.
Topic 2 of the student book.

### Two’s complement (1)

Unsigned integers
Up to now, you have been working with unsigned integers.
These are whole numbers that are positive (0 or higher).
But what if you want to represent negative numbers?
In what situations might you need to represent negative numbers?

### Two’s complement (1)

Negative numbers
Computers cannot recognise the symbols ‘+’ or ‘-’.
These need to be represented in binary in some way.
One method is to replace the most significant bit (MSB) with a sign
bit.
This means that the leftmost bit will be 0 for positive numbers and 1
for negative numbers.
This method of representing signed numbers is called sign and
magnitude.
What would these binary numbers be in denary using this method?
1000  0000
What might the problems be with this method?

### Two’s complement (1)

An alternative…
Another method is called two’s complement.
The most significant bit is a minus number as well as a sign bit.
–128 64 32 16               8  4  2                                                        1
1     0               0  0  1  1  0                                                        1
-128                        8  4                                                           1 = –115
The largest positive number that can be represented is 0111 1111
(i.e. +127)
The largest negative number that can be represented is 1000 0000
(i.e. –128)
Using two’s complement means there is only one value for 0.

### Two’s complement (1)

Conversion method
In two’s complement, positive numbers are the same as normal.
Example:
–128 64 32 16         8421
0000                0111
4 2 1 = +7
IMPORTANT
Note that the answer is +7, not just 7
This is important as this is a signed integer.
It must have the sign present.

### Two’s complement (1)

Conversion method
In two’s complement, negative numbers look quite different from their
unsigned equivalents.
Example:
–128 64 32 16         8421
-128 64 32 16
8                  2 1 = -5
0000                  0101
4                                                        1 = +5

### Two’s complement (1)

Conversion method
You’ve looked at binary to denary conversions for two’s
complement, but how do you go back the other way?
For positive numbers, it’s just the same as you’ve done previously
using subtraction.
For negative numbers, there are some extra steps:
- convert the unsigned equivalent into 8-bit binary
- flip the bits (each 1 becomes a 0 and vice versa)
- add 1 (arithmetically, not appending).

### Two’s complement (1)

Worked Example
Let’s take the number -22 and convert it into binary using two’s
complement.
- 22 into 8-bit binary ������ 0001 0110
- flip the bits ������ 1110 1001
- add 1 ������ 1110 1010.

### Two’s complement (1)

Wrap up: you have learned how to…
✔ Identify the difference between signed and unsigned integers.
✔ Describe how positive and negative numbers are represented in
two's complement.
✔ Find the two's complement of a signed binary number.

---

**Source PDFs:** `2. Data/L4 Two’s complement (1).pdf`.
