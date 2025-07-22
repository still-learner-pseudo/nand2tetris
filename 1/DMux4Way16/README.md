# DMux4Way16

The DMux4Way16 gate takes a 16-bit input and routes it to one of four 16-bit outputs, based on a 2-bit selector.

The HDL code uses a hierarchy of smaller DMux gates to split the input according to the selector bits. Only one output receives the input; the others are set to zero. The implementation is modular and reuses previously built gates for clarity and simplicity.