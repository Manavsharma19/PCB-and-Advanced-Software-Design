**Embedded Systems Project: STM32 PCB and Advanced Software Design**

**Overview**

This project combines hardware design and software development for embedded systems. It involves creating an STM32-based PCB, enhancing a C AST interpreter, implementing file system commands for an SD card, and exploring graphics optimization and console emulator design.

**Key Features**

**1. STM32 PCB Design**  

Used KiCad to design a PCB based on STM32 microcontrollers.
Process included component selection, schematic design, DRC checks, and Gerber file generation.

**2. Java-Based C AST Interpreter**

Enhanced a Java interpreter to handle complex expressions, if, while, and for loops.
Implemented ARM assembly code generation for control structures.

**3. SD Card Firmware Operations**
Developed commands for file system operations:
ls to list files and sizes.
cat to display file contents.
mv to rename files.
copy to duplicate files.
Used QEMU to emulate SD card functionality.

**4. Graphics Optimization**  
Researched and implemented double buffering to reduce flicker and improve animation quality.

**5. Emulator Design (GBA)**  
Explored Game Boy Advance (GBA) architecture, including the ARM7tdmi processor, memory management, and display timing.
Studied techniques for efficient firmware and emulator design.
