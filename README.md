Development of a 32-bit Risc-V processor as part of a university study project. To utilize the processor, you must input Risc-V instructions into the RAM registers as desired, then progressively pass the information through the processor. At the end, the data resides in the register bank.

Some operations to test the processor :

JAL 12 :
0b00000000110000000000000001101111

ADDI RS1, r0, +2 :
0b00000000001000000000000010010011

ADDI RS2, r0, +3 :
0b00000000001100000000000100010011

ADD RS1 + RS2 :
0b00000000001000001000000110110011

BGE r2, r1, PC+8
0b00000000000100010101010001100011

SUB rs3, rs2, rs1
0b01000000000100010000000110110011
