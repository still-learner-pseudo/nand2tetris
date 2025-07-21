# Mux4Way16 Gate

The Mux4Way16 gate selects one of four 16-bit inputs (a, b, c, d) to output, based on a 2-bit selector.

In the HDL code, two Mux16 gates first select between (a, b) and (c, d) using the least significant selector bit. A third Mux16 then chooses between those results using the most significant selector bit. This structure efficiently implements the 4-way selection logic.