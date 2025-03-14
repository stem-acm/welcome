# How Code is Executed in a Computer

When a program runs on a computer, it goes through several stages to transform from human-readable code to instructions the computer can actually execute. Here's how it works:

## The Execution Process

1. **Writing the code**: A programmer writes instructions in a programming language
2. **Compilation/Interpretation**: This code is translated into machine code
3. **Loading**: The operating system loads the program into memory
4. **Execution**: The CPU reads and executes the instructions one by one
5. **Termination**: The program completes its task and ends

## Programming Language Hierarchy

Programming languages exist on a spectrum from low-level (closer to hardware) to high-level (closer to human language):

### Low-level Languages
- **Machine Code**: Binary instructions (0s and 1s) directly executed by the CPU
- **Assembly Language**: Uses human-readable mnemonics that directly correspond to machine instructions

### Mid-level Languages
- **C**: Provides more abstraction than assembly while maintaining hardware control
- **C++**: Adds object-oriented features to C while preserving low-level capabilities

### High-level Languages
- **Python, JavaScript, Java**: Focus on programmer productivity with significant abstraction
- **SQL, MATLAB**: Domain-specific languages for particular applications
- **Visual programming languages**: Block-based programming like Scratch

The higher the level, the more abstraction is provided, making code easier to write and understand but potentially less efficient.

## Translation Process

Code must be translated into machine code before execution through one of these methods:

- **Compilation**: The entire program is translated into machine code before execution (C, C++, Rust)
- **Interpretation**: The program is translated and executed line by line (Python, JavaScript)
- **Just-In-Time (JIT) Compilation**: Code is compiled during execution (Java, C#)

## Input/Output Concept

Input/Output (I/O) refers to how programs interact with the outside world:

### Input
- Data that enters the program from external sources
- Examples: keyboard typing, mouse clicks, file reading, network requests
- Input devices: keyboard, mouse, microphone, sensors

### Output
- Data that the program sends to external destinations
- Examples: text on screen, audio from speakers, data written to files
- Output devices: monitor, speakers, printers

### I/O Processing
1. Program requests input or prepares output
2. Operating system handles the communication with physical devices
3. Data is transferred between the program and the external world

I/O operations are fundamental to making programs useful since they allow interaction with users and other systems.