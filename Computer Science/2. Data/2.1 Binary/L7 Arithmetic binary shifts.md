# L7 Arithmetic binary shifts

**Pearson Edexcel GCSE Computer Science (1CP2) — specification 2.1.4.**

> Notes converted from the lesson slides listed below. They are grouped under the matching specification section.

## L7 Arithmetic binary shifts

### Arithmetic binary shifts

Learning objectives
In this lesson you will learn to:
- apply arithmetic left and right shifts to signed binary numbers
- describe how an arithmetic right shift differs from a logical right
shift.

### Arithmetic binary shifts

Left arithmetic shifting
Shifts are known as ‘bitwise operations' because they operate on
each bit in a pattern, one at a time.
Left-shift  00010111  (decimal 23)
= 0 0 1 0 1 1 1 0 0 (decimal 46)
The Most Significant Bit (MSB) is shifted left, out of the pattern.
Each remaining bit is shifted left to the next location.
A new 0 is placed into the vacated location on the right (the Least
Significant Bit - LSB).
This has the effect of multiplying by 2.
Left arithmetic shifting is the same as left logical shifting.

### Arithmetic binary shifts

Right arithmetic shifting
The LSB is shifted right, out of the pattern.
The most significant bit (MSB) value is always maintained. It is copied into
the vacated location on the left. In this example a 0 is inserted.
This has the effect of dividing by 2, while maintaining the sign.
Right-shift               00 0 1 0 1 1 1  (decimal 23)
= 00001011      (decimal 11)
In multiple shifts, the MSB is duplicated and inserted into all empty spaces.
Right arithmetic shifting is different to right logical shifting as, instead of a 0
being inserted, the value of the most significant bit is maintained.
For this example, and for most unsigned integers, the same effect is
produced. You will see a difference with signed integers.

### Arithmetic binary shifts

Signed integers
Let's look at a signed integer and perform a left arithmetic shift of 3.
The signed integer is a two's complement binary of -22:
First shift   11010100                                                                          -44
Second shift
Third shift   10101000                                                                          -88
01010000                                                                          80
Is there a problem here?
-88 x 2 should be -176

### Arithmetic binary shifts

Overflow
We've looked at overflows before.
An overflow error is when the result of a calculation is too large
for the space allocated for it.
We've just seen the effect that overflows have when performing
shifts.

### Arithmetic binary shifts

Wrap up: you have learned how to…
✔ Apply arithmetic left shifts to signed binary numbers:
- Arithmetic left shifting is the same as logical left shifting.
- Overflow is likely when shifting signed integers.
Apply arithmetic right shifts to signed binary numbers.
✔
✔ Explain how an arithmetic shift right differs from a logical shift
right.
- Arithmetic right shifting maintains the MSB and duplicates it in
every vacant position.
- Logical right shifting fills in with 0s on the left.

---

**Source PDFs:** `2. Data/L7 Arithmetic binary shifts.pdf`.