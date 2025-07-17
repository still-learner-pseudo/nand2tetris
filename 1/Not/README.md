# Not Gate

The Not gate outputs the opposite of its input: 0 becomes 1, and 1 becomes 0.

In the HDL code, this is implemented using a single Nand gate with both inputs connected to the same signal. This leverages the property that Nand(a, a) is equivalent to Not(a).