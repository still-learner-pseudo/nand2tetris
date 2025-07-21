# Or8Way Gate

The Or8Way gate outputs 1 if any of its 8 input bits is 1, otherwise it outputs 0. It's useful for checking if at least one bit in a group is set.

The HDL code chains together standard Or gates to combine all 8 inputs into a single output. Each Or gate takes two inputs, and the outputs are connected in sequence to reduce the 8 inputs to one result.