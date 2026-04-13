<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

2-bit adder: takes in Carry in, A1, A2, B1, B2, where Carry in is a carry bit, A1 is A's 1s bit, A2 is A's 2s bit, B1 is B's 1s bit, and B2 is B's 2s bit. 

## How to test

Insert a two bit number to A by inserting its 1s bit to A1 and its 2s bit to A2. Do the same for B with another 2 bit number. Use Cin as a carry bit for the purpose of chaining multiple instances of this circuit together (carry out of one circuit goes into the carry in of the next). The output is a 3 bit number C, where C1 is its 1s bit, C2 is its 2s bit, and C3 is its 3s bit. When chaining multiple instances of this circuit together, use C3 as the carry out bit. 

## External hardware

three LEDs
