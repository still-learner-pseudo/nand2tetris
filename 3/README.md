# Nand2Tetris – Project 3: Sequential Logic – Memory Elements

Welcome! This repo contains my solutions for Project 3 of the [Nand2Tetris](https://www.nand2tetris.org/) course (also available on [Coursera](https://www.coursera.org/learn/build-a-computer)). In this project, I built the fundamental memory elements that allow a computer to store and retrieve information, starting from a single-bit register and scaling up to a full RAM module.

## What This Project Is About

Project 3 is all about sequential logic and memory. Unlike the previous projects, which focused on combinational logic, here we design circuits that can "remember" values over time. Using the DFF (data flip-flop) as a primitive, I implemented registers, counters, and RAM chips of various sizes.

All implementations were tested using the official test scripts provided in the course, and outputs were verified to match the expected results.

## Memory Elements I’ve Implemented

Here's the list of memory circuits built for this project:

- **Bit:** A single-bit register that stores one bit of data.
- **Register:** A 16-bit register for storing a word.
- **RAM8:** 8 registers of 16 bits each, addressable by a 3-bit address.
- **RAM64:** 64 registers of 16 bits each, addressable by a 6-bit address.
- **RAM512:** 512 registers of 16 bits each, addressable by a 9-bit address.
- **RAM4K:** 4096 registers of 16 bits each, addressable by a 12-bit address.
- **RAM16K:** 16,384 registers of 16 bits each, addressable by a 14-bit address.
- **Program Counter (PC):** A 16-bit counter that can increment, reset, or load a value.

> Each circuit has its own folder containing:
> - `.hdl` – My implementation
> - `.tst` – Test script (from the course)
> - `.cmp` – Expected output (from the course)
> - `.out` – Actual output from running tests

## How to Run the Tests

You can test everything using the [Nand2Tetris Web IDE](https://nand2tetris.github.io/web-ide/):

1. Open the Web IDE.
2. Paste or load the `.hdl` code for the circuit you're testing.
3. Load the `.tst` file (usually auto-loaded in the IDE).
4. Click "Run" and compare the output with the `.cmp` file.

If you're using the offline tools, just load the `.tst` script in the Hardware Simulator and run it.

## Notes & Credits

- All `.tst`, `.cmp`, and test-related materials are provided by the creators of the Nand2Tetris course — Shimon Schocken and Noam Nisan.
- My contributions here are just the `.hdl` implementations and this documentation.
- The goal is to help others learn by example — but if you're taking the course, I strongly recommend trying it on your own first!

## License Info

My HDL implementations and this `README.md` are released under the [MIT License](LICENSE).

Files from the official course (like `.tst` and `.cmp`) are © Nand2Tetris (Nisan & Schocken, MIT Press) and are included here for educational purposes only.

---

Feel free to fork this repo or use it for reference, but remember — the best way to learn is by building it yourself.
