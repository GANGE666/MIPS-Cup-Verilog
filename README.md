# MIPS-Cup-Verilog
<<<<<<< HEAD

Single Cycle CPU can execute add, sub, and, or, slt, addi, lw, sw, beq, j, sll, lui, slti, bne, ori, andi, srl，jal, jr, jalr, addu and subu.

=======


A classic 5-stage pipeline MIPS 32-bit processor.

1. 256K RAM

2. 128K Cache

3. 5 stage: Fetch, Decode, Execute, Memory and Write back

4. The processor support follow insrtuction

	1 TYPE-R: AND, OR, ADD, SUB, SLT, NOR, SRL
	2 TYPE-I: ADDI, ANDI, ORI, XORI, LUI, SLTI
	3 MEM: LW, SW
	4 BRANCH: BEQ, BNE
	5 JUMP: J, JAR, JR, JALR

5. If you want a single cycle process, you can use the code of first commit.
>>>>>>> Pipeline processor
