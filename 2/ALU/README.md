# ALU (Arithmetic Logic Unit)

The ALU performs a variety of arithmetic and logic operations on two 16-bit inputs, controlled by selector bits. It can compute addition, bitwise AND, negation, zeroing, and more, and also outputs flags for zero and negative results.

The HDL code implements the ALU by chaining together multiplexers, adders, and logic gates to process the inputs according to the control signals. Test scripts are provided to verify all supported operations.