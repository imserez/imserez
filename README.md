# Hi! I’m Sergi Juárez

**Computer Architecture | RISC-V Systems | FPGA Prototyping | HPC & HW/SW Co-Design**

I specialize in **CPU microarchitecture, RISC-V systems, and High-Performance Computing (HPC)**. I love bridging the gap between hardware design (RTL/FPGA) and low-level software (C, UNIX, Kernels).

**Skills**: SystemVerilog, Verilog, C/C++, RISC-V, FPGA, Linux, OpenMP, Intel PIN, Python, Bash  

## Here Are Some Projects

* [**HPC Performance Analysis**](https://github.com/imserez/HPC-Performance-Analysis)
  * Hardware profiling of the NAS CG Benchmark using **Intel PIN** and **PMUs** to demonstrate the "Memory Wall" effect and thread scalability bottlenecks (automated via Python/Make).
* **HaDes-V (RISC-V Processor Core)**
  * Custom 32-bit RISC-V (RV32I) 5-stage pipelined processor core built from scratch in **SystemVerilog**, verified with **Verilator** and GTKWave.
  * Developed as part of the official **[RISC-V International Community Challenge](https://community.riscv.org/events/details/risc-v-international-risc-v-academy-presents-community-challenge-with-hades-v/)**. Currently implementating the WB stage.
  * This repository is private due to competition rules. Access can be granted upon request.
* [**rv-microkernel**](https://github.com/imserez/rv-microkernel)
  * Minimal operating system kernel (~1000 LOC) written from scratch in **C** focusing on RISC-V hardware abstraction and SBI interaction via **QEMU**.
* **FPGA Prototyping Modules**
  * Hardware modules (FSMs, timing constraints) implemented on Xilinx boards. 
  * ↳ [UART Transceiver](https://github.com/imserez/fpga-uart) | [Counter](https://github.com/imserez/fpga-counter)
* [**HDLBits Solutions**](https://github.com/imserez/hdlbits)
  * My personal solutions to the HDLBits **Verilog** practice platform (Combinational/sequential logic, state machines).
* [**Pipex**](https://github.com/imserez/pipex)
  * Replicates UNIX shell piping and redirections (`< file1 cmd1 | cmd2 > file2`) using `dup2` and file descriptors.
* [**Arduino Game of Life**](https://github.com/imserez/Colorful-game-of-life-)
  * Conway’s Game of Life optimized for low-memory microcontrollers, featuring bitwise state encoding and **SPI** rendering.
* [**Philosophers**](https://github.com/imserez/philosphers)
  * The classic Dining Philosophers problem solved using **POSIX threads** and mutexes to avoid deadlocks and data races.

---
**Connect**: [LinkedIn](https://www.linkedin.com/in/sergijuarez)
