# Mux8Way16

The Mux8Way16 gate selects one of eight 16-bit inputs to pass to the output, based on a 3-bit selector.

In the HDL code, two Mux4Way16 gates first select between groups of four inputs, and a final Mux16 chooses between those two results using the most significant selector bit. This structure efficiently implements the 8-way selection using smaller multiplexers.