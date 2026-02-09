# 🌟 **Hi there! I'm Sergi Juárez** 👋

---

## 🛠️ **Technical Skills**

| Domain | Technologies |
| :--- | :--- |
| **Hardware Design** | ![Verilog](https://img.shields.io/badge/Verilog-B81D24?style=flat-square&logo=verilog&logoColor=white) ![SystemVerilog](https://img.shields.io/badge/SystemVerilog-181717?style=flat-square) ![Vivado](https://img.shields.io/badge/Xilinx%20Vivado-CA0000?style=flat-square&logo=amd&logoColor=white) |
| **Systems Programming** | ![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white) ![Assembly](https://img.shields.io/badge/Assembly-555555?style=flat-square&logo=gnu&logoColor=white) ![RISC-V](https://img.shields.io/badge/RISC--V-504DFF?style=flat-square&logo=riscv&logoColor=white) |
| **Embedded & OS** | ![Linux Kernel](https://img.shields.io/badge/Linux_Kernel-FCC624?style=flat-square&logo=linux&logoColor=black) ![GNU Make](https://img.shields.io/badge/Makefiles-000?style=flat-square&logo=gnu&logoColor=white) ![UART/GPIO](https://img.shields.io/badge/UART%20%2F%20GPIO-Hardware-orange?style=flat-square) |
| **DevOps & Tools** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GDB](https://img.shields.io/badge/GDB-Debugger-green?style=flat-square) ![Valgrind](https://img.shields.io/badge/Valgrind-MemCheck-darkred?style=flat-square) |
| **Scripting** | ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |

---

## 🏗️ **Featured Projects**

<details open>
<summary>🔩 <b>Hardware, Kernel & Embedded</b> (High Priority)</summary>
<br>

1. **riscv-microkernel** - OS Kernel in ~1000 Lines
   <br>
   ![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
   ![Assembly](https://img.shields.io/badge/Assembly_(RISC--V)-555555?style=flat-square&logo=riscv&logoColor=white)
   ![OS Dev](https://img.shields.io/badge/OS_Dev-Kernel-black?style=flat-square)
   - 📦 **Key Features:** A minimal operating system kernel written from scratch. Handles booting, basic context switching, and trap handling on RISC-V architecture.
   - 🔗 [View Repository](https://github.com/imserez/rv-microkernel)

2. **FPGA Projects** (UART & Counter)
   <br>
   ![Verilog](https://img.shields.io/badge/Verilog-B81D24?style=flat-square&logo=verilog&logoColor=white)
   ![Vivado](https://img.shields.io/badge/Vivado-CA0000?style=flat-square&logo=amd&logoColor=white)
   ![Hardware](https://img.shields.io/badge/Hardware-Logic_Gates-orange?style=flat-square)
   - 📦 **Key Features:** Implementation of hardware logic on Xilinx FPGA. Includes a binary counter and a custom UART communication module to interface with a PC.
   - 🔗 [View FPGA Counter](https://github.com/imserez/fpga-counter) | [View FPGA UART](https://github.com/imserez/fpga-uart)

3. **Arduino Game of Life** - Embedded Graphics
   <br>
   ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
   ![Embedded](https://img.shields.io/badge/Embedded-Microcontroller-success?style=flat-square)
   - 📦 **Key Features:** Conway's Game of Life optimized for low-memory microcontrollers, rendering directly to a TFT screen with SPI communication. Uses bitwise operations for state management.
   - 🔗 [View Repository](https://github.com/imserez/Colorful-game-of-life-)

</details>

<details>
<summary>🐧 <b>Unix Architecture & Systems (42 Cursus)</b></summary>
<br>

1. **Minishell** - Bash-like Shell Implementation
   <br>
   ![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
   ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
   ![Process Management](https://img.shields.io/badge/Process-Fork%2FExec-blue?style=flat-square)
   - 📦 **Key Features:** A fully functional shell. Manages parsing, specific path execution, environment variables, signals, and piping logic similar to Bash.
   - 🔗 [View Repository](https://github.com/imserez/minishell) 2. **Philosophers** - Concurrency & Threading
   <br>
   ![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
   ![Threads](https://img.shields.io/badge/Threads-Mutex_%26_Deadlocks-red?style=flat-square)
   - 📦 **Key Features:** Solves the "Dining Philosophers" problem using POSIX threads and mutexes, focusing on avoiding deadlocks and race conditions.
   - 🔗 [View Repository](https://github.com/imserez/philosphers)

3. **Pipex** - UNIX Pipes Mechanism
   <br>
   ![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
   ![I/O](https://img.shields.io/badge/UNIX-File_Descriptors-lightgrey?style=flat-square)
   - 📦 **Key Features:** Replicates the behavior of shell pipes (`|`) and redirections, handling file descriptors (`dup2`) and child process communication.
   - 🔗 [View Repository](https://github.com/imserez/pipex)

4. **Custom C Libraries** (Printf, Get_Next_Line, Libft)
   <br>
   ![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
   ![Memory](https://img.shields.io/badge/Memory-Buffer_Management-blueviolet?style=flat-square)
   - 📦 **Key Features:** - **ft_printf:** Re-implementation of `printf` managing variadic arguments (`stdarg.h`).
     - **get_next_line:** Efficient file reading using **static variables** and buffer management to read lines from file descriptors.
   - 🔗 [View Printf](https://github.com/imserez/printf) | [View Get_Next_Line](https://github.com/imserez/get_next_line) </details>

<details>
<summary>⚡ <b>Algorithms & Graphics (C++ / Optimization)</b></summary>
<br>

1. **Cub3D** - Raycasting Engine (Wolfenstein 3D style)
   <br>
   ![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
   ![Graphics](https://img.shields.io/badge/Graphics-Raycasting-ff69b4?style=flat-square)
   - 📦 **Key Features:** A 3D graphical project using raycasting mathematics to render a maze from a first-person perspective.
   - 🔗 [View Repository](https://github.com/imserez/cub3d) 2. **Push_swap** - Sorting Algorithm Complexity
   <br>
   ![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
   ![Algorithms](https://img.shields.io/badge/Algo-Complexity_Analysis-yellow?style=flat-square)
   - 📦 **Key Features:** Sorting data on a stack with a limited set of instructions, optimized for the minimum number of operations (Algorithmic complexity focus).
   - 🔗 [View Repository](https://github.com/imserez/push_swap)

3. **CPP Modules** - Object Oriented Programming
   <br>
   ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
   ![OOP](https://img.shields.io/badge/Paradigm-OOP-green?style=flat-square)
   - 📦 **Key Features:** Extensive exploration of C++98 standards, classes, inheritance, polymorphism, templates, and exception handling.
   - 🔗 [View Repository](https://github.com/imserez/cpp-modules) </details>

## 📫 **Let's Connect!**

I am eager to apply my skills in a professional environment that challenges me to push the limits of embedded technology.

* **LinkedIn:** [Sergi Juárez](https://www.linkedin.com/in/sergijuarez/)
* **Location:** Barcelona, Spain
