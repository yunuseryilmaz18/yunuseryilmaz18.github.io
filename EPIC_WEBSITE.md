---
layout: "page"
title: "LITERALLY EPIC WEBSITE"
permalink: /epic/
---
# crypto-coprocessor

A cryptographic coprocessor (CCP) written in Verilog HDL.

**IMPORTANT: It works on behavioral simulation but the synthesis never finishes because DSA verification block contains multiple amounts of 2048 and 4096 bit D-FF and latches.**

## File contents:
- `docs` folder contains documents about CCP.

- `src` folder contains design files.

- `sim` folder contains testbench files.

- `waveform_configs` folder contains Vivado Waveform Configuration files for various scenarios.

`top_module.v` is the top module and `tb_top` is its testbench.
The same rule can be applied to the other design and testbench files.