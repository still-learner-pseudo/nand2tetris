# Mux Gate

The Mux (multiplexer) gate selects one of two inputs (a or b) to output, based on the value of the selector input (sel). If sel is 0, the output is a; if sel is 1, the output is b.

In the HDL code, this is implemented using Not, And, and Or gates: Not inverts sel, And gates combine the inputs with the selector, and Or merges the results to produce the final output.