# FullAdder

The FullAdder circuit adds three single bits (two inputs and a carry-in) and produces a sum and a carry-out.

The HDL code implements this by chaining two HalfAdders and an Xor gate to combine the carries, allowing correct addition with carry propagation.