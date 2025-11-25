- **[NoRWX] Proof-of-Concept**  
  *Purpose:* Demonstrates running position-independent (PIC) x86-64 machine code to output "Hello World" in RW-only memory, without marking it executable.  
  *Key Features:* No executable memory required, security-focused demonstration.  
  *Technologies Used:* x86-64 assembly, C.  
  *Status:* Experimental, for research and educational use.  
  *Audience:* Security researchers, low-level programmers.  
  [See details](content/NoRWX/)

  - Implements a hardware breakpoint and vectored exception handler (VEH) to emulate x86-64 instructions in RW memory, never marking code as executable.
  - Includes an emulator for arithmetic, logic, control flow, stack, and WinAPI calls.
  - Example: Runs a HelloWorld shellcode blob using only RW memory and VEH.

- **[PIS] Position-Independent String**  
  *Purpose:* Provides utilities for handling strings in a position-independent way, useful for memory-safe and relocatable code.  
  *Key Features:* String manipulation without fixed memory addresses.  
  *Technologies Used:* C, custom algorithms.  
  *Status:* In development.  
  *Audience:* Systems programmers.  
  [See details](content/PIS/)

  - Solves the problem of lost string literals in shellcode by merging .data/.rdata into .text via linker script.
  - Includes runtime relocation logic and pattern scanning for x86/x64 shellcode.
  - Example: Provides code for scanning function prologues and relocating data pointers.

- **[EC] Armenian Encoding Converter**  
  *Purpose:* Converts Armenian text between different character encodings.  
  *Key Features:* Supports multiple Armenian encodings, batch conversion.  
  *Technologies Used:* C#, .NET 9.  
  *Status:* Beta.  
  *Audience:* Linguists, developers working with Armenian text.  
  [See details](content/EC/)

  - Core library for text, Word, and Excel file conversion using a mapping file.
  - CLI for batch/single-file conversion; GUI in progress.
  - Requires Windows and Microsoft Office for document conversion.

- **[c-shellcode] Minimal Windows Shellcode Demo**  
  *Purpose:* Demonstrates manual Windows API resolution and shellcode techniques in C.  
  *Key Features:* No standard library, manual PE parsing, works on x86/x64.  
  *Technologies Used:* C, Windows internals.  
  *Status:* Experimental.  
  *Audience:* Low-level programmers, security researchers.  
  [See details](content/c-shellcode/)

  - Locates PEB, enumerates modules, parses PE headers, and resolves exported functions manually.
  - Prints "Hello world!" using only resolved addresses, no standard library calls.
  - Includes build scripts and custom type definitions for Windows internals.