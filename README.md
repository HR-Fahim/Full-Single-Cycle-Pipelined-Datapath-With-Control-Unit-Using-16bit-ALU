# About

This repository contains the implementation of a Single Cycle Datapath, where each component of the datapath executes an instruction once per cycle. The fetch-decode-execute sequence is generated using components of the Single-Cycle Datapath to create a Multi-Cycle (pipelined) Datapath. In the pipelined Datapath, functional units such as the register file, data memory, and ALU can be utilized multiple times during the execution of an instruction, resulting in reduced hardware and cost.<br/>

<sub> ****P.S.*** The project was completed under CSE332 (Computer Organization and Architecture) course offered by North South University.*<sub/>

# Project Details

The project implements a full Single-Cycle Pipelined Datapath with a Control Unit using a 16-bit ALU. The Single-Cycle Pipelined Datapath is divided into various components, including:

- **Memory:** This component holds the current instruction.
- **ALU:** It processes the current instructions.
- **Program Counter (PC):** It maintains the address of the current instruction.

These components are interconnected to create the basic Datapath.

# Experiment Details

The project utilizes a 16-bit ISA with the following instruction formats:

- **R-type:**

| op (4 bit) | rs (4 bit) | rt (4 bit) | rd (4 bit) |
| ---------- | ---------- | ---------- | ---------- |

- **I-type:**

| op (4 bit) | rs (4 bit) | rt (4 bit) | immediate (4 bit) |
| ---------- | ---------- | ---------- | ----------------- |

- **J-type:**

| op (4 bit) | Target (12 bit) |

# Requirements

- Logisim Tool

# Pipelined Datapath Diagram

The diagram below illustrates the schematic for the entire Single-Cycle Datapath with pipeline registers placed between the phases:

![Pipelined-version-of-the-MIPS-datapath](https://user-images.githubusercontent.com/66734379/189549236-6077a273-8347-4b39-86fb-42450b547222.png)

> **Note:** This diagram represents the collected version.

# License

The code in this repository is provided under the [GNU License](LICENSE). Please refer to the license file for more details, limitations, and responsibilities.

# Extra

As a bonus, some additional simple `ALU` projects have been included in this repository along with the main project.

# Support

Support this project in the following ways:

- Star the repository.
- Follow me on [GitHub](https://github.com/HR-Fahim).
- Share this project on sites like Hacker News, Twitter, Reddit, etc.
- Report any bugs, glitches, or errors.

Thank you for your support!
