# Hi, I'm Luka 👋

I'm a Computer Science Specialist graduate from the **University of Toronto**, passionate about systems programming, performance engineering, and building reliable software.

---

## 🛠️ Tech Stack

**Languages:** C++, C, Rust, TypeScript, Ruby, C#, SQL  
**Frontend:** Angular, React Native  
**Backend:** .NET, Node.js  
**Tools & Infra:** LLVM, CMake, Makefile, Git, SQL Server  
**Concepts:** Systems Programming, Parallel & High-Performance Computing, Computer Architecture, Compilers, ERP/Enterprise Systems

---

## 💼 Experience

### Software Developer — Sparkrock (formerly Edsembli)

---

## 🚀 Projects

### 🔧 Open Source

**[SerenityOS — Process::die() scheduler fix](https://github.com/SerenityOS/serenity/pull/26555)** · C++  
Patched a concurrency bug by clearing the stopped state in `Process::die()` while holding the scheduler lock, ensuring threads can correctly resume and clean up their kernel stacks before exiting.

---

### ⚡ Performance & Systems

**[Optimized Matrix Multiplication](https://github.com/lukarajic/Optimized-Matrix-Multiplication)** · C++, Makefile  
Incrementally optimized CPU matrix multiplication from a naive triple-loop (~1.7 GFLOPS) to ~120 GFLOPS on Apple Silicon, a **~70x speedup**, using cache blocking, SIMD vectorization, and multi-threading. A deep dive into memory hierarchy, ILP, and TLP.

**[Simple CPU Emulator](https://github.com/lukarajic/Simple-CPU-Emulator)** · C++, Makefile  
A 5-stage pipelined **RISC-V (RV32I)** CPU emulator in modern C++. Implements pipeline orchestration, hazard resolution, memory-mapped I/O, and a cache hierarchy.

**[Parallel Algorithm Implementation](https://github.com/lukarajic/Parallel-Algorithm-Implementation)** · C++, Shell, CMake  
High-performance C++ implementation of the **N-Body problem** optimized for multi-core CPUs, demonstrating parallel computing, algorithmic optimization, and memory architecture.

**[Compiler Optimization](https://github.com/lukarajic/Compiler-Optimization)** · C++, CMake, LLVM  
A custom compiler pipeline and **LLVM optimization pass** that translates a high-level frontend language into optimized x86-64 assembly.

---
