# Risc-V 32bit Processor

This repository contains the development of a 32-bit Risc-V processor as part of a university project.

To utilize the processor, follow these steps:

1. Open the file `processeur.dig` to start using the processor.

2. Input Risc-V instructions into the RAM registers as desired.

3. Progressively pass the information through the processor.

4. At the end, the data resides in the register bank.

## Operations to Test the Processor

Here are some example operations to test the processor:

1. **JAL 12**: `0b00000000110000000000000001101111`

2. **ADDI RS1, r0, +2**: `0b00000000001000000000000010010011`

3. **ADDI RS2, r0, +3**: `0b00000000001100000000000100010011`

4. **ADD RS1 + RS2**: `0b00000000001000001000000110110011`

5. **BGE r2, r1, PC+8**: `0b00000000000100010101010001100011`

6. **SUB rs3, rs2, rs1**: `0b01000000000100010000000110110011`

Feel free to explore and test the processor with these operations. If you encounter any issues or have any questions, don't hesitate to ask me !
