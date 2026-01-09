---
title: RUMasm
abbreviations:
  
---

(runasm)=
# RUMasm

> Algorithms for Big Data Lab - University of Rhode Island

## Macro Assembler for the Rust Universal Machine (RUM)

I helped build a macro assembler in Rust for the Rust Universal Machine (RUM), the little RISC‑style virtual machine used in our Machine Organization course. The whole idea was to give students a clearer, more hands‑on way to understand how assembly actually works.

One of the bigger pieces I worked on was an algorithm that links multiple assembly files into a single executable, complete with relocation entries. That made it possible to split programs across files and piece them together cleanly, basically giving students a more realistic, modular workflow.

We also built the assembler so it includes template code blocks where students fill in the logic for core instructions like add, subtract, load, and store. It’s a simple setup, but it gets them working directly with instruction set design and the nitty‑gritty of machine‑level behavior, which is where everything finally clicks.



Skills: Rust, Assembly, Systems Programming, Linker Design, RISC Architecture, Binary Relocation
