# Nand2Tetris – Project 2: Arithmetic Circuits & ALU

Welcome! This repo contains my solutions for Project 2 of the [Nand2Tetris](https://www.nand2tetris.org/) course (also available on [Coursera](https://www.coursera.org/learn/build-a-computer)). In this project, I built key arithmetic circuits and the ALU (Arithmetic Logic Unit) that form the computational core of a computer.

## What This Project Is About

Project 2 focuses on constructing arithmetic and logic circuits from the ground up, using only the basic gates built in Project 1. The main highlight is the ALU, which can perform a variety of operations (addition, bitwise AND, negation, zeroing, etc.) on 16-bit inputs, controlled by several selector bits.

All implementations were tested using the official test scripts provided in the course, and outputs were verified to match the expected results.

## Circuits I’ve Implemented

Here's the list of circuits built for this project:

- **HalfAdder:** Computes the sum and carry of two bits.
- **FullAdder:** Computes the sum and carry of three bits (two inputs plus carry-in).
- **Add16:** Adds two 16-bit numbers.
- **Inc16:** Increments a 16-bit number by 1.
- **ALU:** The Arithmetic Logic Unit, capable of performing multiple operations on two 16-bit inputs, with status outputs for zero and negative results.

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
