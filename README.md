# C Sandbox – Clean Build Starter

This repository is a minimal C project used to verify a clean development
environment on Linux (WSL) using GCC and VS Code.

The goal is to establish a baseline C project that:
- Compiles without warnings
- Uses an explicit C standard
- Follows basic best practices
- Serves as a starting point for future C experiments and tools

---

## Build Environment

- OS: Ubuntu (WSL)
- Compiler: GCC
- Editor: Visual Studio Code (WSL mode)
- C Standard: C11
- Version Control: Git / GitHub

---

## Build Instructions

Compile with warnings enabled:

```bash
gcc -Wall -Wextra -std=c11 main.c -o main
