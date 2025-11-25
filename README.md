- **[NoRWX] Proof-of-Concept**  
  *Purpose:* Demonstrates running position-independent (PIC) x86-64 machine code to output "Hello World" in RW-only memory, without marking it executable.  
  *Key Features:* No executable memory required, security-focused demonstration.  
  *Technologies Used:* x86-64 assembly, C.  
  *Status:* Experimental, for research and educational use.  
  *Audience:* Security researchers, low-level programmers.  
  [See details](content/NoRWX/)

- **[PIS] _[Position-Independent Code: Relocate]_ Position-Independent String**  
  *Purpose:* Provides utilities for handling strings in a position-independent way, useful for memory-safe and relocatable code.  
  *Key Features:* String manipulation without fixed memory addresses.  
  *Technologies Used:* C, custom algorithms.  
  *Status:* In development.  
  *Audience:* Systems programmers, low-level programmers, security researchers.  
  [See details](content/PIS/)

- **[c-shellcode] _[Position-Independent Code: Shellcode]_ Minimal Windows Shellcode Demo**  
  *Purpose:* Demonstrates manual Windows API resolution and shellcode techniques in C.  
  *Key Features:* No standard library, manual PE parsing, works on x86/x64.  
  *Technologies Used:* C, Windows internals.  
  *Status:* Experimental.  
  *Audience:* Systems programmers, low-level programmers, security researchers.  
  [See details](content/c-shellcode/)

- **[c-peb] _[Position-Independent Code: Prologue]_ Windows PEB parsing**  
  *Purpose:* Demonstrates accessing and parsing the Windows Process Environment Block (PEB) manually for API resolution in position-independent code.  
  *Key Features:* No standard library, direct PEB access, manual PE parsing, compatible with x86/x64.  
  *Technologies Used:* C, Windows internals.  
  *Status:* Experimental.  
  *Audience:* Systems programmers, low-level programmers, security researchers.  
  [See details](content/c-peb/)
	
- **[EC] Armenian Encoding Converter**  
  *Purpose:* Converts Armenian text between different character encodings.  
  *Key Features:* Supports multiple Armenian encodings, batch conversion.  
  *Technologies Used:* C#, .NET 9.  
  *Status:* Beta.  
  *Audience:* Linguists, developers working with Armenian text.  
  [See details](content\EC\)
