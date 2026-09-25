# L9 ASCII

**Pearson Edexcel GCSE Computer Science (1CP2) — specification 2.2.1.**

> Notes converted from the lesson slides listed below. They are grouped under the matching specification section.

## L9 ASCII

### ASCII

Learning objectives
In this lesson you will learn to:
- describe how characters are represented in 7-bit ASCII
- derive the ASCII code for one character when given the code
for another
- outline the shortcomings of ASCII and understand how
encoding systems that use more bits overcome them.
For more information about this topic and additional student activities
see Topic 2 of the student book.

### ASCII

How computers store data
You have previously learned that computers represent all kinds of
information in binary.
You have also learned that binary can be encoded in different ways to
represent different kinds of information.
What types of information can you currently represent?
Unsigned integers Signed integers
Another kind of information that computers need to store is text.

### ASCII

ASCII
One way to encode binary to store text is to use ASCII.
ASCII is the American Standard Code for Information Interchange.
It was created in the 1960s as a standard way to encode text on
early computers.

### ASCII

Why is it necessary?
Imagine if everyone used a different encoding scheme for text.
A          A
1101 1000  1000 1000
If one group used the encoding on the right, and another group the encoding on
the left, then they would not be able to communicate.
ASCII enables computing devices to communicate with one another and to
translate their communication into identical information.

### ASCII

Bit patterns
You previously learned how to calculate the number of unique
characters that can be represented using a set number of bits.
ASCII uses 7 bits.
How many values can you represent with 7 bits?
Can you remember how to calculate that?
Number of patterns = 2n, where n is the number of bits.
ASCII patterns = 27 = 128

### ASCII             ASCII lookup table

This is an ASCII
lookup table.
It shows the
numbers
associated with
each character
in the ASCII
character set.
A character set
is a list of the
characters that
a computer is
able to
translate.

### ASCII

Patterns
Whilst you are not expected to memorise the ASCII table, there are a
couple of patterns that will help you to generate the codes.
The capital letter alphabet starts at denary 65 and the lower case
alphabet starts at denary 97.
‘A’ is 65 in denary and is 0100 0001 in binary.
‘a’ is 97 in denary and is 0110 0001 in binary.
The upper and lower case alphabets have matching binary patterns.

### ASCII

Finding patterns
Character  Denary                       Binary
A       65                      0100 0001
a       97                      0110 0001
What do you add to the code for ‘A’ to find the code for ‘a’?
Character  Denary                       Binary
G       71                     0100 0111
g      103                     0110 0111
What do you subtract from the code for ‘g’ to find the code for ‘G’?

### ASCII

Deriving characters
It is possible to derive the ASCII value of a character if you know
the ASCII value of another.
Worked example:
The binary code for ‘A’ is 0100 0001.
You need the ASCII value for ‘E’.
From ‘A’ to ‘E’ is 4 characters, so add 4 (in binary) to the value
for ‘A’.
So the binary value for ‘E’ is 0100 0101.

### ASCII

Limitations
ASCII represents 128 unique characters.
Are there any missing that you can think of?
ASCII is suitable for English (and languages that use the same
characters), but it cannot represent languages that have additional
different characters.
French, German, Cyrillic, and Mandarin are examples of the
hundreds of languages that do not fit into ASCII.
For these languages Unicode was created. The first version is able
to represent 120,000 characters.
≠×÷©®™¥

### ASCII

Wrap up: so far you have learned how to…
✔ Define what is meant by the term 'character set’.
- All the characters that a computer is able to represent and translate.
✔ Describe how characters are represented in 7-bit ASCII.
- Each character is represented with a 7-bit binary pattern. The alphabets
in upper and lower case have matching patterns.
Derive the ASCII code for one character when given the code for another.
✔
- The logical organisation of the ASCII table allows you to work this out
by counting between the characters.
Outline the shortcomings of ASCII and understand how encoding systems
✔
that use more bits overcome them.
- 7 bits only give 128 possible values. For more characters, more bits
need to be used.

---

**Source PDFs:** `2. Data/L9 ASCII.pdf`.
