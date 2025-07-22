# DMux8Way Gate

The DMux8Way gate takes a single input and routes it to one of eight outputs, based on a 3-bit selector. Only one output will be 1; the rest will be 0.

The HDL code builds this gate by combining smaller DMux and DMux4Way gates in a hierarchical structure, using the selector bits to control the routing. Each output is activated only when the selector matches its index.