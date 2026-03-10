# Hi! I’m Sergi Juárez 

**Systems Software Engineer | Embedded & Low-Level Software | RISC-V | FPGA & HW/SW Interface**

I’m a systems-oriented engineer interested in working at the **intersection of software and hardware**. I’m currently focusing on **embedded and low-level systems**, with particular interest in **system bring-up**, **RISC-V architectures**, and the **hardware/software interface**.

> *“The best way to understand a system is to build it.”*

---

## About Me

### Background

I come from a **dual educational path**:

- **UOC** — Computer Architecture & Operating Systems  
- **42 Barcelona** — intensive, peer-to-peer, project-based learning  

This combination shaped how I approach engineering problems: **self-driven learning**, deep debugging, and collaborative problem-solving in complex systems.

---

### Current Focus — Hardware / Software Interface

I’m actively moving towards **Hardware–Software Co-Design**, approaching it primarily from the **software side**:

- Operating system internals  
- Embedded systems & bare-metal programming  
- Firmware development  
- RISC-V ISA and toolchains  

In parallel, I’m building hands-on experience on the **hardware side**:

- FPGA prototyping using **Verilog / SystemVerilog**
- Design exploration and simulation with **Vivado**
- Early system bring-up and validation
- Understanding how software stacks interact with hardware platforms  

To bridge both worlds, I’m prototyping designs on a **Xilinx FPGA**, focusing on reproducible workflows, clear documentation, and iterative testing. Seeing low-level software concepts materialize as real hardware has been a key learning experience.

---

I’m currently deepening my understanding of **RISC-V systems**, where my interests in operating systems, embedded software, and FPGA prototyping naturally converge, with the goal of contributing to the **open-source hardware ecosystem**.

---

## 🛠️ Technical Skills

| Domain | Technologies |
|------|-------------|
| **Hardware Design** | Verilog, SystemVerilog, Vivado |
| **Systems Programming** | C, C++, Assembly, RISC-V |
| **Embedded & OS** | Linux, Kernel fundamentals, GNU Make, UART / GPIO |
| **DevOps & Tools** | Git, Docker, GDB, Valgrind |
| **Scripting** | Bash, Python |

---

## Featured Projects

<details open>
<summary>🔩 <b>Hardware, Kernel & Embedded</b></summary>
<br>

> ### 1. **HaDes-V** — RISC-V Processor Core `[WIP]`
> ![SystemVerilog](https://img.shields.io/badge/SystemVerilog-005288?style=flat-square&logo=verilog&logoColor=white)
> ![RISC-V](https://img.shields.io/badge/RISC--V-504DFF?style=flat-square&logo=riscv&logoColor=white)
> ![FPGA](https://img.shields.io/badge/CPU-Architecture-orange?style=flat-square)
>
> - 📦 **What it is:** A custom 32-bit RISC-V (RV32I) pipelined processor core built from scratch.
> - 🧠 **Focus:** RTL design, instruction fetch/decode/execute pipeline, ALU implementation, and testbench verification with Verilator/GTKWave.
> - 🔗 [View Repository](https://github.com/imserez/HaDes-V)
>
> ---
>
> ### 2. **FPGA Projects** — UART & Counter  
> ![SystemVerilog](https://img.shields.io/badge/SystemVerilog-005288?style=flat-square&logo=verilog&logoColor=white)
> ![Vivado](https://img.shields.io/badge/Vivado-CA0000?style=flat-square&logo=amd&logoColor=white)
> ![FPGA](https://img.shields.io/badge/FPGA-Logic-orange?style=flat-square)
>
> - 📦 **What it is:** FPGA-based hardware modules implemented on Xilinx boards.
> - 🧠 **Focus:** Finite State Machines (FSM), timing constraints, and HW/SW interfacing.
> - 🔗 [Counter](https://github.com/imserez/fpga-counter) | [UART](https://github.com/imserez/fpga-uart)
>
> ---
>
> ### 3. **riscv-microkernel** — Minimal OS Kernel `[Paused]`
> ![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
> ![RISC-V](https://img.shields.io/badge/RISC--V-504DFF?style=flat-square&logo=riscv&logoColor=white)
> ![OS Dev](https://img.shields.io/badge/OS-Kernel-black?style=flat-square)
>
> - 📦 **What it is:** A minimal operating system kernel written from scratch (~1000 LOC).
> - 🧠 **Focus:** Hardware abstraction, privilege modes, and SBI interaction via QEMU.
> - 🔗 [View Repository](https://github.com/imserez/rv-microkernel)
>
> ---
>
> ### 4. **Arduino Game of Life** — Embedded Graphics  
> ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
> ![Embedded](https://img.shields.io/badge/Embedded-MCU-success?style=flat-square)
>
> - 📦 **What it is:** Conway’s Game of Life optimized for low-memory microcontrollers.
> - 🧠 **Focus:** Bitwise state encoding, SPI communication, and real-time rendering.
> - 🔗 [View Repository](https://github.com/imserez/Colorful-game-of-life-)
>
> ---
>
> ### 5. **HDLBits Solutions** — Hardware Design Practice
> ![Verilog](https://img.shields.io/badge/Verilog-B81D24?style=flat-square&logo=verilog&logoColor=white)
>
> - 📦 **What it is:** My personal solutions to the HDLBits Verilog practice platform.
> - 🧠 **Focus:** Combinational/sequential logic, state machines, and RTL design patterns.
> - 🔗 [View Repository](https://github.com/imserez/hdlbits)

</details>

---

<details>
<summary>🐧 <b>Unix Architecture & Systems</b></summary>
<br>

> ### 1. **Minishell** — Bash-like shell  
> ![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
> ![UNIX](https://img.shields.io/badge/UNIX-Fork%2FExec-blue?style=flat-square)
>
> - 📦 Parsing, process creation, signals, pipes, redirections, environment handling.
> - 🔗 [View Repository](https://github.com/9x14S/42-Cursus-minishell)
>
> ---
>
> ### 2. **Philosophers** — Concurrency & Threading  
> ![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
> ![Threads](https://img.shields.io/badge/Threads-Mutex-red?style=flat-square)
>
> - 📦 Dining Philosophers solved using POSIX threads and mutexes.
> - 🔗 [View Repository](https://github.com/imserez/philosphers)
>
> ---
>
> ### 3. **Pipex** — UNIX Pipes  
> ![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
> ![I/O](https://img.shields.io/badge/UNIX-I%2FO-lightgrey?style=flat-square)
>
> - 📦 Replicates shell piping and redirections using `dup2` and file descriptors.
> - 🔗 [View Repository](https://github.com/imserez/pipex)
>
> ---
>
> ### 4. **Custom C Libraries**  
> ![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
> ![Memory](https://img.shields.io/badge/Memory-Management-blueviolet?style=flat-square)
>
> - **ft_printf** — variadic arguments, format parsing  
> - **get_next_line** — buffered file reading with static state  
> - 🔗 [Printf](https://github.com/imserez/printf) | [GNL](https://github.com/imserez/get_next_line)

</details>

---

<details>
<summary>⚡ <b>Algorithms & Graphics</b></summary>
<br>

> ### 1. **Cub3D** — Raycasting Engine  
> ![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
> ![Graphics](https://img.shields.io/badge/Graphics-Raycasting-ff69b4?style=flat-square)
>
> - 📦 Wolfenstein-style 3D engine using raycasting math.
> - 🔗 [View Repository](https://github.com/9x14S/42-Cursus-Cub3d)
>
> ---
>
> ### 2. **Push_swap** — Algorithmic Optimization  
> ![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
> ![Algorithms](https://img.shields.io/badge/Algorithms-Complexity-yellow?style=flat-square)
>
> - 📦 Stack-based sorting optimized for minimal operations.
> - 🔗 [View Repository](https://github.com/imserez/push_swap)
>
> ---
>
> ### 3. **CPP Modules** — Object-Oriented Programming  
> ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
> ![OOP](https://img.shields.io/badge/OOP-Design-green?style=flat-square)
>
> - 📦 C++98 deep dive: inheritance, polymorphism, templates, exceptions.
> - 🔗 [View Repository](https://github.com/imserez/cpp-modules)
> 
> ---
>
> ### 4. **so_long** — 2D graphics project 
> ![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
> ![Graphics](https://img.shields.io/badge/Graphics-Raycasting-ff69b4?style=flat-square)
>
> - 📦 so_long is a minimal 2D graphics project that involves building a simple game engine using the MiniLibX library. I've also developed a tester to verify that the map is valid.
> - 🔗 [so_long](https://github.com/imserez/so_long) | [tester](https://github.com/imserez/so_long_tester)

</details>

---

## 📫 Let’s Connect

I’m eager to apply my skills in environments where **low-level software meets real hardware**.

- **LinkedIn:** [Sergi Juárez](https://www.linkedin.com/in/sergijuarez/)
- **Location:** Barcelona, Spain
