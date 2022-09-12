# About
In a Single Cycle Datapath, each of the Datapath's components executes an instruction once. Therefore, no Datapath component may be utilized more than once each cycle. The fetch-decode-execute sequence, in this case, was created using components of a Single-Cycle Datapath to generate a Multi-Cycle (pipelined) Datapath. Each functional unit (such as a register file, data memory, or ALU) in a multicycle, and particularly in the pipelined Datapath, can be used more than once during the execution of an instruction, saving hardware (and, thus, reducing cost).<br/>

<sub> ****P.S.*** It was a part of project from CSE332 course offered by CSE, NSU (North South University).*<sub/>
# Project Details
16-bit ALU has been used to build a full Single-Cycle Pipelined Datapath with a Control Unit. A full Single-Cycle Pipelined Datapath is distributed in different parts including <br/>
- `Memory`; among the components of a very basic part is `Memory`, which holds the current instruction.
- `ALU` that processes current instructions and `Program Counter` or `PC` that maintains the address of the current instruction.<br/>
These straightforward parts are connected together & create a fundamental Datapath.
# Experiment Details
16-bit ISA with the fields listed below (Here, instruction is presented in the following formats):<br/>
- **_R-type_**<br/>

| op (4 bit)  | rs (4 bit)  | rt (4 bit)  | rd (4 bit)  |
| ----------- | ----------- | ----------- | ----------- |
- **_I-type_**<br/>

| op (4 bit)  | rs (4 bit)  | rt (4 bit)  | immediate (4 bit)  |
| ----------- | ----------- | ----------- | ------------------ |
- **_J-type_**<br/>

| op (4 bit)  | Target (12 bit)  | 
| ----------- | ---------------- | 

# Requirements
- Logisim Tool
# Pipelined Datapath Diagram
The schematic for the entire Single-Cycle Datapath, with pipeline registers placed in-between the phases, is shown below:<br/>
![Pipelined-version-of-the-MIPS-datapath](https://user-images.githubusercontent.com/66734379/189549236-6077a273-8347-4b39-86fb-42450b547222.png)<br/>
> Collected Diagram
# Extra
Some extra simple `ALU` projects have been added with the main project as a bonus.
# Support [<sup> @github/support <sup/>](https://support.github.com/)
Assist the project in a number of ways:
- Star the repository.
- Follow me on [GitHub](https://github.com/HR-Fahim).
- Please share on the sites like Hacker News, Twitter, Reddit, etc.
- Report for any bugs, glitches, or errors.<br />

Thank you!
