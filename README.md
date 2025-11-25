### [**[NoRWX] Proof-of-Concept**](https://mrzaxaryan.blog/content/NoRWX/)  
**Purpose:** Demonstrates running position-independent (PIC) x86-64 machine code to output "Hello World" in RW-only memory, without marking it executable.  
**Key Features:**  
  
 - No executable memory required  
 - Hardware breakpoints + VEH technique  
 - Security-focused demonstration  
  
**Technologies Used:** x86-64 assembly, C.  
**Status:** Experimental, for research and educational use.  
**Audience:** Security researchers, low-level programmers.  

---

### [**[PIS][_Position-Independent Code: Relocate_] Position-Independent String**](https://mrzaxaryan.blog/content/PIS/)  
**Purpose:** Tools and techniques for handling strings in fully position-independent and relocatable code (PIC).  
**Key Features:**
 
 - Embed and retrieve strings without fixed addresses  
 - Useful for shellcode, PIC, loaders  

**Technologies:** C, custom algorithms  
**Status:** In development  
**Audience:** Systems programmers, low-level developers, security researchers 

---

### [**[c-shellcode][_Position-Independent Code: Shellcode_] Minimal Windows Shellcode Demo**](https://mrzaxaryan.blog/content/c-shellcode/)  
**Purpose:** Minimal Windows shellcode implementation in C with manual API resolution.  
**Key Features:**
 
 - No CRT / no standard library  
 - Manual PEB walking and PE export parsing  
 - Works on x86 and x64  

**Technologies:** C, Windows internals  
**Status:** Experimental  
**Audience:** Systems programmers, reverse-engineers, security researchers

---

### [**[c-peb][_Position-Independent Code: Prologue_] Windows PEB parsing**](https://mrzaxaryan.blog/content/c-peb/)  
**Purpose:** Demonstrates direct access to the Windows PEB for module lookup and API resolution.  
**Key Features:**

 - Direct TEB/PEB access  
 - Manual PE export table parsing  
 - No imports, no standard library, position-independent  

**Technologies:** C, Windows internals  
**Status:** Experimental  
**Audience:** Systems programmers, low-level programmers, security researchers

---

### [**[EC] Armenian Encoding Converter**](https://mrzaxaryan.blog/content/EC/)  
**Purpose:** Converts Armenian text between multiple encodings (ANSI, Unicode, ArmSCII, etc.).  
**Key Features:**

 - Supports multiple Armenian encodings  
 - Batch conversion  
 - Word/Excel converters (TXT/DOC/DOCX/XLS/XLSX)  

**Technologies:** C#, .NET 9  
**Status:** Beta  
**Audience:** Linguists, developers dealing with Armenian text, localization engineers
