# L2 Unsigned integers

**Pearson Edexcel GCSE Computer Science (1CP2) — specification 2.1.2, 2.1.3.**

> Notes converted from the lesson slides listed below. They are grouped under the matching specification section.

## L2 Unsigned integers

### Unsigned integers

Learning objectives
In this lesson you will learn to:
- define the terms 'nibble' and 'byte'
- convert between denary and 8-bit binary numbers.

### Unsigned integers

Numbers
Previously, you learned that all data is represented using binary in a
digital computer.
One type of data that needs to be represented is numerical data.
You will be looking at a particular set of numbers: unsigned
integers.
This means whole, positive numbers (more than or equal to 0).

### Unsigned integers

Numbers
Humans count using denary numbers (base 10).
We use 10 symbols: 0, 1, 2, 3, 4, 5, 6, 7, 8 and 9.
This is because we have ten fingers.
You already know how denary numbers work.
103               102        101         100
1000               100         10           1
4           9
5                 0    (4 x 10 =
(5 x 1000 =        (0 x 100 =      40)    (9 x 1 = 9) = 5049
+ 40         +9
5000)                0)
5000               +0

### Unsigned integers

Resources
Computers count using binary numbers (base 2).
They use just 2 symbols: 0 and 1
23                 22  21         20
8                  4   2          1
1                  1   0          1
(1 x 8 = 8) (1 x 4 = 4) (0 x 2 = 0) (1 x 1 = 1)                                                      = 13
8                  +4  +0         +1

### Unsigned integers

Counting
Let's count in binary together:
Remember 2n where n = 4, gives us 16 unique values, 0 through

### Unsigned integers

Nibbles
A set of 4 bits (binary digits) is called a nibble.
A single nibble can store 16 unique values (24) – the denary numbers, 0
to 15.
We can use a table to help us remember the place value of each
column.
8                  4           2                                                                     1
0                  1           1                                                                     0
To convert this binary number back to denary, we can add the column
values which contain the digit 1.
So the bit pattern 0110 is the same as 4 + 2, which equals 6.

### Unsigned integers

Nibbles
You can also convert from a denary number into its binary equivalent.
You can use the same table to help you. However, instead of adding,
you'll subtract.
For example, to convert 13 in denary into binary:
- Largest column value that fits: 8
- Put a 1 in the 8 column
- 13 – 8 = 5; move along a column
- 5 – 4 = 1
- Put a 1 in the 4 column; nothing left.
- 13 in denary = 1101 in binary.
8  4  2  1
1  1  0  1

### Unsigned integers

Bytes
Two nibbles make a byte. A byte is 8 binary digits.
A byte is the standard unit of measurement in digital computing.
A byte can represent 256 values (0 to 255 in denary).
Converting uses the same process as with a nibble, but with more
columns.
128 64 32 16 8  4  2                                                                 1
1  0  0  0  0   1  1                                                                 0
So this binary number converted to denary would be: 128 + 4 + 2 =
134.

### Unsigned integers

Most significant bit
It is important to remember that all binary patterns are written from
the largest value to the smallest value, as shown in the table.
Exactly the same approach is used for the normal denary numbers
that we use every day.
128 64 32 16 8                 4  2                                                                  1
1                  0  0  0  1  1  0                                                                  0
In binary numbers we use the term most significant bit (MSB) to
refer to the leftmost bit in any binary number.
This means that the leftmost digit has the largest place value.

### Unsigned integers

Wrap up: you have learned how to…
✔ Define the terms 'nibble' and 'byte'.
- A byte is 8 bits. A nibble is half a byte or 4 bits.
✔ Convert between denary and 8-bit binary numbers.
- Adding place values for binary to denary.
- Subtracting place values for denary to binary.
✔ Describe what is meant by the term ‘most significant bit'.

---

**Source PDFs:** `2. Data/L2 Unsigned integers.pdf`.
