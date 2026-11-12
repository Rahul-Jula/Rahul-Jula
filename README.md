# Rahul Jula

**ASIC Design · RTL Design · Digital Design**

I'm pursuing an MSE in Electrical Engineering at Arizona State University, graduating in May 2027. I enjoy turning an architecture into working hardware, tracing a design through simulation, and understanding what changes when it reaches synthesis and layout.

Available for **Spring 2027 co-ops** and **full-time design roles from May 2027**.

[LinkedIn](https://www.linkedin.com/in/rahul-jula) · [Email](mailto:rjula@asu.edu)

## Featured hardware projects

### [Programmable Tensor Data-Movement ASIC with Multicast NoC](https://github.com/Rahul-Jula/tensor-data-movement)

A 4x4 SystemVerilog network-on-chip with descriptor-driven DMA, multicast routing, and asynchronous clock boundaries. Reworking the DMA to stream cached-word elements reduced the FP16 read reissue interval from **19 to 10 cycles** at matched memory latency. Matched synthesis reported **1.37% lower cell area**, and RTL data-movement co-simulation with modeled compute used **12.66% fewer cycles** than baseline DMA across twelve BERT-Base encoder layers.

Explore the [RTL and architecture](https://github.com/Rahul-Jula/tensor-data-movement#architecture), [streaming DMA](https://github.com/Rahul-Jula/tensor-data-movement/blob/main/experiments/streaming_dma/tensor_dma.sv), and [scoped results](https://github.com/Rahul-Jula/tensor-data-movement#results-with-comparison-boundaries).

### [GCN Accelerator for Node Classification](https://github.com/Rahul-Jula/gcn-accelerator)

A six-node, three-class accelerator with a shared **96-term dot-product datapath**, sparse COO aggregation, and FSM-controlled ArgMax. Took the ASAP7 design through synthesis and physical implementation to GDSII. Saved post-route timing reports show **+0.530 ns setup WNS** and **+0.002 ns hold WNS** with zero violating paths.

Explore the [RTL](https://github.com/Rahul-Jula/gcn-accelerator/tree/main/rtl) and [timing and simulation evidence](https://github.com/Rahul-Jula/gcn-accelerator#recorded-implementation-results).

### [Pipelined MIPS Processor](https://github.com/Rahul-Jula/pipelined-mips-processor)

A **32-bit, five-stage processor** with forwarding, load-use stalls, and decode-stage branch resolution. Added `MULADD` and `PERFMON` instructions with an accumulator read port and hardware counters. The base pipeline with OpenRAM SRAM macros met a **1.25 ns synthesis setup constraint**.

Explore the [datapath](https://github.com/Rahul-Jula/pipelined-mips-processor/blob/main/extended/datapath.sv), [custom instructions](https://github.com/Rahul-Jula/pipelined-mips-processor#architecture), and [synthesis scope](https://github.com/Rahul-Jula/pipelined-mips-processor#recorded-results).

## Engineering toolkit

| Area | Experience |
| --- | --- |
| RTL and programming | SystemVerilog, Verilog, Tcl, Python, C |
| Microarchitecture | Datapaths, FSMs, pipelining, hazard handling, DMA, NoCs, clock domain crossing |
| Simulation and debug | Synopsys VCS, Verdi, ModelSim |
| ASIC implementation | Design Compiler, SDC constraints, static timing analysis, Cadence Innovus |

## Background

At ASU, I work as a Graduate Service Assistant for Digital Design Fundamentals, evaluating logic designs and reviewing schematics and simulation waveforms. My ECIL internship involved a Verilog SPI interface for ADAS3022 data acquisition and debugging analog/digital I/O boards.

MSE Electrical Engineering, **Arizona State University** · GPA **3.60/4.00** · Expected May 2027  
B.Tech. Electronics and Communication Engineering, **SRM Institute of Science and Technology** · CGPA **8.70/10.00** · May 2025
