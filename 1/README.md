# Nand2Tetris – Project 1: Elementary Logic Gates

Welcome! This repo contains my solutions for Project 1 of the [Nand2Tetris](https://www.nand2tetris.org/) course (also available on [Coursera](https://www.coursera.org/learn/build-a-computer)). The focus here is on building basic logic gates from the ground up using HDL (Hardware Description Language), starting with just a Nand gate.

## What This Project Is About

Project 1 is all about understanding how digital logic is built using a minimal set of tools. The only gate we're given is the Nand gate, and from that, we implement everything else — from simple gates like Not and And, to more complex ones like multiplexers and multi-bit logic.

All implementations were tested using the official test scripts provided in the course, and outputs were verified to match the expected results.

## Gates I’ve Implemented

Here's the full list of gates I built, in the order I developed them:

- **Basic Gates:** [Not](./Not), [And](./And), [Or](./Or), [Xor](./Xor), [Mux](./Mux), [DMux](./DMux)
- **16-bit Variants:** [Not16](./Not16), [And16](./And16), [Or16](./Or16), [Mux16](./Mux16)
- **Multi-way Gates:** [Or8Way](./Or8Way), [Mux4Way16](./Mux4Way16), [Mux8Way16](./Mux8Way16), [DMux4Way16](./DMux4Way16), [DMux8Way](./DMux8Way)

> For each gate, I created a separate folder containing:
> - `.hdl` – My implementation
> - `.tst` – Test script (from the course)
> - `.cmp` – Expected output (from the course)
> - `.out` – Actual output from running tests

## How to Run the Tests

You can test everything using the [Nand2Tetris Web IDE](https://nand2tetris.github.io/web-ide/). Here's how:

1. Open the Web IDE.
2. Paste or load the `.hdl` code for the gate you're testing.
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
