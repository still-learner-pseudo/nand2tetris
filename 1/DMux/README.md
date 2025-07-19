# DMux Gate

The DMux (Demultiplexer) gate takes a single input and a selector bit, and routes the input to one of two outputs. If the selector is 0, the input goes to output 'a'; if it's 1, the input goes to output 'b'.

The HDL code uses a Not gate to invert the selector and two And gates to direct the input to the correct output based on the selector value.