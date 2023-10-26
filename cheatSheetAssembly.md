# x86 Registers Cheat Sheet

## 32/64-bit General-Purpose Registers:
| Name   | Meaning           | Purpose                              |
|-------|-------------------|--------------------------------------|
| EAX/RAX | Accumulator     | Stores calculation results           |
| EBX/RBX | Base            | Points to data in memory            |
| ECX/RCX | Counter         | Used for loops                       |
| EDX/RDX | Data            | Often used with EAX for extended results |
| ESI/RDI | Source/Destination | Pointers for string operations  |
| ESP/RSP | Stack Pointer    | Manages the stack                    |
| EBP/RBP | Base Pointer     | Points to the base of the stack     |

## Segment Registers:
| Name   | Meaning          | Purpose                  |
|-------|------------------|--------------------------|
| CS    | Code Segment    | Code segment             |
| DS    | Data Segment    | Data segment             |
| ES    | Extra Segment   | Extra segment            |
| FS    | F Segment       | Used for specific tasks  |
| GS    | G Segment       | Used for specific tasks  |
| SS    | Stack Segment   | Stack segment            |

## Index Registers:
| Name   | Meaning          | Purpose                  |
|-------|------------------|--------------------------|
| EIP/RIP | Instruction Pointer | Points to the current instruction |
| EFLAGS/RFLAGS | Flags  | Stores status indicators   |
| ST0-ST7 | FPU Registers  | Used for floating-point calculations (x87 FPU) |
| XMM0-XMM15 | SSE Registers | For SIMD (Single Instruction, Multiple Data) operations |

## Control Registers:
| Name   | Meaning           | Purpose                            |
|-------|-------------------|------------------------------------|
| CR0-CR4 | Control Registers | Control various aspects of the processor |
| DR0-DR7 | Debug Registers   | Used for debugging                  |

## Model-Specific Registers:
| Name   | Meaning                  | Purpose                               |
|-------|--------------------------|---------------------------------------|
| MSRs  | Model-Specific Registers | Control processor-specific features   |
