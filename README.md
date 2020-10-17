OCaml RISC-V Extension
----------------------

## Overview 

The accompanying pdf (`diss.pdf`) contains my dissertation "Optimisations across Software and Hardware using RISC-V" for my computer science degree from Cambridge. The TL;DR is I added custom instructions to [RISC-V](https://riscv.org/) specifically designed to improve OCaml programs compiled to RISC-V.  

> This dissertation looks at how an open-source specification for a modular, flexible, reduced instruction set architecture, RISC-V, can open doors to greater control and manipulation over the hardware-software interface... we can achieve faster and more power-efficient computers simultaneously...

There were many tools modified to make it all happen: 
  - [Spike the RISC-V ISA Simulator](https://github.com/patricoferris/riscv-isa-sim/tree/rv64GO)
  - [GNU Binutils](https://github.com/patricoferris/riscv-binutils-gdb/tree/rv64GO)
  - [The port of the OCaml compiler](https://github.com/patricoferris/riscv-ocaml/tree/rv64GO) because at the time RISC-V hadn't been upstreamed. 
  - [Some specific benchmarks](https://github.com/patricoferris/riscv-benchmarks)
  - [A Spike Analysis Tool](https://github.com/patricoferris/ospike)

## Future Work 

This has only scratched the surface of what is possible. Better custom instructions, MirageOS running on RISC-V... all very exciting! 

## A Note on the quality of work 

In the spirit of being open, especially for other Cambridge students, this dissertation scored `68/100`. Make of that what you will. 

I tried to get more feedback so I could improve and learn, but was told "...unfortunately the Cambridge system doesn't allow for feedback on final results". Make of that what you will... I learned a lot, enjoyed it and the feedback from my supervisor (and friends) was great. 