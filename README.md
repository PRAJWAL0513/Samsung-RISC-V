# Samsung RISC-V Workshop Documentation

Welcome to the **Samsung RISC-V Workshop Documentation**. This guide provides an overview of tasks designed to introduce participants to the RISC-V Instruction Set Architecture (ISA), along with step-by-step instructions for setting up the development environment and exploring essential concepts.

---

## 📋 Table of Contents

- [Task 1: RISC-V ISA and GNU Toolchain](#task-1-risc-v-isa-and-gnu-toolchain)
- [License](#license)

---

## 🛠️ Task 1: RISC-V ISA and GNU Toolchain

### Overview

This task provides an introduction to the RISC-V Instruction Set Architecture (ISA) and walks through the setup of the development environment using the **VSDSquadron RISC-V board**. Participants will gain hands-on experience with running C programs, cross-compiling for RISC-V, and analyzing the generated assembly and memory architecture.

---

### 🔧 Implementation Steps

#### 1. Running a C Program in Ubuntu

Set up your environment to execute a C program. Follow the command flow and configuration instructions as depicted in the figure below.

![RISC-V GNU Toolchain Setup](images/vsd1.png)

---

#### 2. C Program for Summing `n` Integers

Develop a simple C program to calculate the sum of `n` integers. The figure below illustrates the cross-compilation workflow for executing this program on a RISC-V processor.

![Cross-Compilation Workflow](images/vsd2.png)

---

#### 3. Examining Generated RISC-V Assembly Code

Analyze the assembly code generated during cross-compilation. This step helps in understanding the mapping of high-level C constructs to RISC-V assembly instructions.

![Assembly Code Analysis](images/vsd3.png)

---

#### 4. Memory Architecture Analysis (Main Function)

Study the memory layout of the `main` function, including stack, heap, and other memory sections. The figure below highlights the memory mapping details for a RISC-V program.

![Memory Mapping Details](images/vsd4.png)

---

## 📝 License

This project documentation is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

---

We hope this documentation serves as a valuable resource for your journey into RISC-V development. Happy coding! 🎉
