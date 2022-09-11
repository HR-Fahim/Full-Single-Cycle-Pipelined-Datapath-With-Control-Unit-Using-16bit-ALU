# About
In a single cycle datapath, each of the datapath's components executes an instruction once. Therefore, no datapath component may be utilized more than once each cycle. The fetch-decode-execute sequence in this case was created using components of a single-cycle datapath to generate a multi-cycle (pipelined) datapath. Each functional unit (such as a register file, data memory, or ALU) in multicycle, and particularly in pipelined datapath, can be used more than once during the execution of an instruction, saving hardware (and, thus, reduces cost).
# Project Details
16 bit ALU has been used to  build a full single cycle pipelined datapath with control unit. A full single cycle pipelined datapath is distributed in different parts including:<br/>
- `Memory`; among the components of a very basic part is `Memory`, which holds the current instruction.
- `ALU` that processes current instructions and `Pogram Counter` or `PC` that maintains the address of the current instruction.<br/>
These straightforward parts are connected together & create a fundamental datapath.
# Experiment Details
16 bit ISA with the fields listed below (Here, instruction is presented in the following formats) :<br/>
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
The schematic for the entire single cycle datapath, with pipeline registers placed in-between the phases, is shown below :<br/>
![Pipelined-version-of-the-MIPS-datapath](https://user-images.githubusercontent.com/66734379/189549236-6077a273-8347-4b39-86fb-42450b547222.png)<br/>
> Collected Diagram
# Extras
Some extra simple `ALU` projects have been added with the main project as bonus.
# Support
Assist the project in a number of ways:
- Star the repository.
- Follow me on GitHub.
- Please share on the sites like Hacker News, Twitter, Reddit, etc.
- Report for any bugs, glitches, or errors. <br />
Thank you!
