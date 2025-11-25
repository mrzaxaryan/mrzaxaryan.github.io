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

### [**[PIS][Position-Independent Code: Relocate] Position-Independent String**](https://mrzaxaryan.blog/content/PIS/)  
**Purpose:** Tools and techniques for handling strings in fully position-independent and relocatable code (PIC).  
**Key Features:**

 - No imports, no standard library, position-independent 
 - Embed and retrieve strings without fixed addresses  
 - Useful for shellcode, PIC, loaders  

**Technologies:** C, custom algorithms  
**Status:** In development  
**Audience:** Systems programmers, low-level developers, security researchers 

---

### [**[c-shellcode][Position-Independent Code: Shellcode] Minimal Windows Shellcode Demo**](https://mrzaxaryan.blog/content/c-shellcode/)  
**Purpose:** Minimal Windows shellcode implementation in C with manual API resolution.  
**Key Features:**
 
 - No imports, no standard library, position-independent
 - Direct TEB/PEB access   
 - Works on x86 and x64 

**Technologies:** C, Windows internals  
**Status:** Experimental  
**Audience:** Systems programmers, reverse-engineers, security researchers

---

### [**[c-peb][Position-Independent Code: Prologue] Windows PEB parsing**](https://mrzaxaryan.blog/content/c-peb/)  
**Purpose:** Demonstrates direct access to the Windows PEB for module lookup and API resolution.  
**Key Features:**

 - Direct TEB/PEB access  
 - PEB walking
 - Works on x86 and x64 

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

---