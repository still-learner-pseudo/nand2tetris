# Add16

The Add16 circuit adds two 16-bit binary numbers and outputs their 16-bit sum. It ignores any carry out from the most significant bit.

The HDL code uses a HalfAdder for the least significant bit and a chain of FullAdders for the remaining bits, passing the carry along the chain to compute the correct sum for each bit position.