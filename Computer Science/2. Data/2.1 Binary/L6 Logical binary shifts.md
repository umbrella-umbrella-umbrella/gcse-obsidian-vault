# L6 Logical binary shifts

**Pearson Edexcel GCSE Computer Science (1CP2) — specification 2.1.4.**

> Notes converted from the lesson slides listed below. They are grouped under the matching specification section.

## L6 Logical binary shifts

### Logical binary shifts

Learning objectives
In this lesson you will learn to:
- apply logical left and right shifts to binary integers
- use logical binary shifts to multiply and divide unsigned binary
integers by powers of 2
- explain why a number may be less precise after a binary shift
right has been applied.

### Logical binary shifts

Binary arithmetic
You've learned how to add in binary, but what about other
operations?
Multiplication and division can be achieved using shifting.
There are two forms of shifting:
logical and
arithmetic.

### Logical binary shifts

Logical left shifting
Shifts are known as ‘bitwise operations' because they operate on
each bit in a pattern, one at a time.
Left-shift             00010111  (decimal 23)
= 0 0 1 0 1 1 1 0 0 (decimal 46)
The MSB is shifted left, out of the pattern.
Each remaining bit is shifted left to the next location.
A new 0 is placed into the vacated location on the right (LSB).
This has the effect of multiplying by 2.
NB MSB – most significant bit
LSB – least significant bit

### Logical binary shifts

Logical right shifting
The LSB is shifted right, out of the pattern.
A 0 is always inserted into the vacated MSB.
This has the effect of dividing by 2.
Right-shift     00010111  (decimal 23)
(decimal 11)
= 00001011
This causes a loss of precision.
23 divided by 2 should be 11.5, but we can only currently represent
integers.
The 0.5 is lost.
This means that the result is less precise.
The more right shifts you perform, the more precision you may lose.

### Logical binary shifts

Shifting more than once
What effect would shifting three times have?
How would you work out the effect?
You know that one shift divides or multiplies by two.
You should remember that binary is base two, which means that
each column value is a multiple of two.
Shifting is the same, each shift is another divide or multiply by
two.
For example, shifting three times would be the same as dividing
or multiplying by 8.

### Logical binary shifts

Wrap up: so far you have learned how to…
✔ Apply logical left and right shifts to binary integers.
- Shifting left one position – a new 0 is shifted in on the right
(LSB).
- Shifting right one position – a new 0 is shifted in on the left
(MSB).
✔ Use logical binary shifts to multiply and divide unsigned binary
integers by powers of 2.
- Each shift is another power of two.
✔ Explain why a number may be less precise after a binary shift right
has been applied
- Decimal places are lost when you divide by shifting.

---

**Source PDFs:** `2. Data/L6 Logical binary shifts.pdf`.