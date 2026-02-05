It's a fundemental of how a computer and system works and how software interacts with the hardware. 

## 1. CPU Architecture and Execution :

- CPU(Central Processing Unit) : Brain of the computer that executes instructions.
- Registers : Small & fast storage inside the CPU used to hold temperory data. 
- ISA(Instruction Set Architecture) : Set of instruction a CPU follows. Example : Intel follows x86 ISA, ARM follows arm ISA.
- Fetch–Decode–Execute cycle : Process where CPU runs a instructions. It happens continously inside the processor.
- Flag Register : Holds status bits after arithmetic operations.
- Pipeline : Allows multiple instruction happens at once.
- Branch prediction : CPU guesses which way a decision will go berfore knowing for sure so it saves time.
- Privilege levels : User mode and kernal mode.

## 2. Memory and Addressing : 

- Memory Hieraarchy : Registers(fast) -> cache -> RAM -> Disk(slow)
- Cache : fast memory inside the CPU that stores recently used data for quick access.
- Virtual Memory : Its a technique that allows computer to use part of its storage as an extension of RAM.
- Paging : Splits memory into Fixed blocks called pages for easy management.
- TLB(Translation Lookaside Buffer) : It stores recent virtual-physical translation to make it faster.
- Stack : Special type of memory strcuture that stores in Last in First Out(LIFO) order.
- Heap : Used to store data dynamically. Example : Loading and viewing image file.
- Addressing Mode : Different ways a CPU can access data like Immediate, Direct, Indirect and indexed.


## 3. Data Representation : 

- Binary/Hexadecimal : Way to represent numbers.
- Two's Complement : How computer represent neagtive numbers in binary.
- Bitwise Operations : AND, OR, XOR.
- Overflow : When a calculation exceeds what the register can hold.


## 4. Assembly Launguage : 

- It's a low-level programming language that uses human-readable instructions to represents binary to CPU understand. 
- Example : MOV R1, #5   ; move the value 5 into register R1.
- Mnemonic : Short name of instructions like
- MOV(Move between registers)
- ADD/SUB(arithmetic)
- JMP(Change flow of execution)
- CMP(compare two values)
- B/BL: Branch or Branch with link 
- PUSH/POP : Store or retrive values on the stack.

## ARM Architecture :-

- ARM(Advanced RISC Machine) is a RISC(Reduced Instruction Set Computer) architecture.
- Used in ARM processor. 
- Used in mobile devices, embedded systems, IoT
- Registers : Typically has 16-32 register.

## x86 Architecture :-

- Since it is used in the Intel 8086(16 bit processor) it is called as x86 and it used CISC(Complex instruction Set computer) for performing multiple operations.
- Used in Intel processor. 
- Used in desktop, server.
