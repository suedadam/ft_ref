# Core War
<p align="center">
  <img src="https://i.ytimg.com/vi/Kcn7Zec4RHY/maxresdefault.jpg">
</p>

The core war project is based off of the [1984 programming game](https://en.wikipedia.org/wiki/Core_War) which has two or more battle programs (warriors) compete for control of the arena's memory space. 
This team project was split into 3 tasks, the virtual machine, the assembelr, and the champion. 

[PDF](pdf/corewar.en.pdf)
---

# Objectives
|Name|TL;DR
|:-:|:-:|
|Compiling|This project required an assembler - a program that built out an AST to parse and transform the assembly text into byte code to be interpreted by the virtual machine.|
|Virtual machine|Creating a virtual machine in C.|
|Assembly language|Have an assembly parser to turn into assembled code (byte code) which is parsed by the virtual machine's scheduler|

# Skills
|Skill|How it was used
|:-:|:-:|
|AST construction & evaluation|The assembler needed to parse the assembly for errors as well as transform it into byte code.|
|Scheduler|The scheduler needed to simulate how a CPU scheduler works by giving each champion a single operation per cycle and evaluating cost per operation|
|Assembly/Redcode|Each team member needed to understand the assembly language in order to accomplish their part. (Assembler/VirtualMachine/Champion)|
|Sandbox virtualization|The virtual machine needed to be an inescapable environment to ensure fair game regardless of what type of champion was loaded into the arena.|
