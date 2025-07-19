# Xor Gate

The Xor (exclusive OR) gate outputs 1 if exactly one of its two inputs is 1, and 0 otherwise. It's commonly used in arithmetic and error detection circuits.

The HDL code implements Xor using only Nand gates, combining them to create the required logic. The design follows the standard Xor formula: (a AND NOT b) OR (NOT a AND b), but realized entirely with Nand-based sub-expressions.