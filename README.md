# CPU-with-5bit-register

1903125: Simulation of a 3 bit CPU in digital simulator app and verifying it's correctness by running a sample a code stored on ROM.

In the first 7 clock cycle, instructions from ROM were copied to RAM. Then the PCenable pin was turned to 1 and ROM was practically disabled. Instructions from RAM began executing in every clock cycle.

Details:
The CPU has the following characteristics:
Word Size of CPU = 3
Register Number = 5
Size of RAM = 7
Word size of ISA and RAM = 16
ALU Operations = ADD, ROL, OR
Branching Operations = JC, JMP
CPU Instructions Modes = Branching Mode, Register Mode, Immediate Mode
RAM = 7x16
Register = 5x3
