<div align="center">

# Luka Rajic

**Systems Engineer · HPC Enthusiast · Open Source Contributor**

[![Email](https://img.shields.io/badge/Email-luka.rajic%40mail.utoronto.ca-c0392b?style=flat-square&logo=gmail&logoColor=white)](mailto:luka.rajic@mail.utoronto.ca)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-lukarajic-0077b5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/lukarajic)
[![GitHub](https://img.shields.io/badge/GitHub-lukarajic-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/lukarajic)

</div>

---


## Projects

### 🔢 [Optimized Matrix Multiplication](https://github.com/lukarajic/Optimized-Matrix-Multiplication) `C++`
Incremental optimization of matrix multiplication from a naive triple-loop (~1.7 GFLOPS) to **~120 GFLOPS on Apple Silicon** — a **70× speedup**. Techniques include cache blocking, SIMD vectorization, and multi-threading. A hands-on study of memory hierarchy, ILP, and TLP.

### ⚙️ [Simple CPU Emulator](https://github.com/lukarajic/Simple-CPU-Emulator) `C++`
A fully functional **5-stage pipelined RV32I RISC-V CPU emulator** in modern C++. Implements pipeline orchestration, hazard resolution, memory-mapped I/O, and cache hierarchy. Validated by executing real compiled binaries.

---

## Open Source


### 🛡️ [SerenityOS: Kernel Race Condition Fix](https://github.com/SerenityOS/serenity/pull/26555) `C++`
Resolved a critical race condition in `Process::die()` by clearing the stopped state under the scheduler lock, ensuring threads can safely resume and clean up their kernel stacks before exit. Prevents deadlocks in the kernel scheduler.

---

## Technical Skills

| Domain | Technologies |
|---|---|
| **Languages** | C++, C, Rust, Python, Ruby, SQL, Assembly (RISC-V / x86) |
| **Systems** | Multithreaded Programming, SIMD, Kernel Sync, Memory Management, ISA Emulation |
| **Performance** | GFLOPS Analysis, Cache Hierarchy, ILP/TLP Optimization |
| **Tooling** | Git, GDB, Valgrind, Bash, Linux, CI/CD, Jira |

---

## Education

**University of Toronto** — H.B.Sc. Computer Science (Specialist), 2020–2026
