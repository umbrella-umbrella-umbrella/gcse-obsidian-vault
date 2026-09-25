# L3 Binary arithmetic

**Pearson Edexcel GCSE Computer Science (1CP2) — specification 2.1.4, 2.1.5.**

> Notes converted from the lesson slides listed below. They are grouped under the matching specification section.

## L3 Binary arithmetic

### Binary arithmetic

Learning objectives
In this lesson students will learn to:
- add together two positive 8-bit binary patterns
- define what is meant by the term 'overflow error'
- describe the effects of an overflow error.

### Binary arithmetic

Adding in binary
One of the most common operations that you will need to carry out is
adding binary numbers together.
The method you will use is the same method you may have been
taught to add denary numbers when you were younger: column
addition.

### Binary arithmetic

Golden rules
There are 4 rules to remember. If you always apply them, you'll get
your binary additions right every time.
0+0=0
0+1=1
1 + 1 = 0 carry 1
1 + 1 + 1 = 1 carry 1

### Binary arithmetic

1    0001             Addition
4+ 0 1 0 0+           In column 1, 1 + 1 = 2; so write a 0
down and carry 1 over into the next
5    0101             column on the left.
1    0001
1+ 0 0 0 1+
2                  1
3   0011             In column 2, 1 + 1 + 1 = 3 lots of 2 = 1
7+  0 1 1 1+         lot of 4 plus 1 lot of 2; so write a 1 down
10                    and carry 1 over into the next column on
111             the left.

### Binary arithmetic

Overflow
Let's try one more together:
1100       0111
1111       0 1 0 0+
1011       1011
1          1
Is this answer correct?
What's happened to the last carry digit?

### Binary arithmetic

Overflow
What you've just seen is called overflow.
It means the result of the calculation is too large for the space allocated
(in this case 1 byte).
The way a computer handles this will depend on how it's setup.
- It could crash and report an overflow error.
- It could truncate the answer (simply leave off the extra one).
- It could wrap the number around back to zero.

### Binary arithmetic

Handling overflow in a manual calculation
Let's look again at our previous example:
1100         0111
1111         0100+
1011         1011
1            1
We know there is one final digit to represent, but because it has
overflowed, we need to be clear that this is the case.
Our final answer should look something like this:
1100   0111
1111   0100+
(1) 1 0 1 1  1011
1      1

### Binary arithmetic

In programming…
Python is a language that is flexible with storage space.
Integers are not limited to a specific number of bits and can expand
to fit available memory.
In some applications, it's important to work out how much space is
‘just enough', particularly when memory might be short.
Such applications include embedded systems where the hardware
is basic.

### Binary arithmetic

Wrap up: you have learned how to…
✔ Add together two positive 8-bit binary integers.
- Using the golden rules:
0+0=0
1+0=1
1 + 1 = 0 carry 1
1 + 1 + 1 = 1 carry 1
✔ Define what is meant by the term 'overflow error'.
- When the result of a calculation is too large for the space
allocated.
✔ Describe the effects of an overflow error.
- An error could be reported, the value could be truncated, or
the number could be wrapped around to 0.

---

**Source PDFs:** `2. Data/L3 Binary arithmetic.pdf`.
