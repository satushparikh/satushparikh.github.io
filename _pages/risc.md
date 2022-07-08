---
layout: archive
title: "IITB-RISC"
permalink: /projects/risc/
author_profile: true
redirect_from:
  - /risc
  - /project/risc
---

Course project for EE309: Microprocessors, Spring 2022  
*with Kalp Vyas, Pulkit Paliwal and Siddhant Bose*   

![Multicycle RTL Netlist](/files/risc_multicycle.png)

IITB-RISC is a 16-bit processor capable of performing basic operations. It has an instruction set architecture (ISA) of 17 instructions such as arithmetic and logical operations, load and store to memory, and branch statements. 

We designed and tested our implementation on VHDL. Our group implemented the ISA using two different processor architectures:

* Multicycle: We divided the processor into two different units, the controller and the datapath. The controller was a Moore FSM and interfaced with the datapath.
* Pipeline: We implemented a 6-stage pipeline consisting of the stages instruction fetch, instruction decode, register read, execute, memory access and register write-back. We took steps to optimize performance by implementing hazard mitigation techniques such as data-forwarding.
