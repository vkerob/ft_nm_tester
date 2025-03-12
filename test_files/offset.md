## **ELF 32-bit Header (Elf32_Ehdr)**

| Field Name | Offset (Hex) | Size | Description |
| --- | --- | --- | --- |
| `e_ident` | `0x00` | 16 bytes | ELF magic number and identification |
| `e_type` | `0x10` | 2 bytes | File type (executable, object, .so, etc.) |
| `e_machine` | `0x12` | 2 bytes | Architecture (x86, ARM, etc.) |
| `e_version` | `0x14` | 4 bytes | ELF version |
| `e_entry` | `0x18` | 4 bytes | Entry point address (program start) |
| `e_phoff` | `0x1C` | 4 bytes | Program header table offset |
| `e_shoff` | `0x20` | 4 bytes | Section header table offset |
| `e_flags` | `0x24` | 4 bytes | Architecture-specific flags |
| `e_ehsize` | `0x28` | 2 bytes | ELF header size |
| `e_phentsize` | `0x2A` | 2 bytes | Size of a program header table entry |
| `e_phnum` | `0x2C` | 2 bytes | Number of program header table entries |
| `e_shentsize` | `0x2E` | 2 bytes | Size of a section header table entry |
| `e_shnum` | `0x30` | 2 bytes | Number of section header table entries |
| `e_shstrndx` | `0x32` | 2 bytes | Index of section header string table |

## **ELF 64-bit Header (Elf64_Ehdr)**

| Field Name | Offset (Hex) | Size | Description |
| --- | --- | --- | --- |
| `e_ident` | `0x00` | 16 bytes | ELF magic number and identification |
| `e_type` | `0x10` | 2 bytes | File type (executable, object, .so, etc.) |
| `e_machine` | `0x12` | 2 bytes | Architecture (x86_64, ARM, etc.) |
| `e_version` | `0x14` | 4 bytes | ELF version |
| `e_entry` | `0x18` | 8 bytes | Entry point address (program start) |
| `e_phoff` | `0x20` | 8 bytes | Program header table offset |
| `e_shoff` | `0x28` | 8 bytes | Section header table offset |
| `e_flags` | `0x30` | 4 bytes | Architecture-specific flags |
| `e_ehsize` | `0x34` | 2 bytes | ELF header size |
| `e_phentsize` | `0x36` | 2 bytes | Size of a program header table entry |
| `e_phnum` | `0x38` | 2 bytes | Number of program header table entries |
| `e_shentsize` | `0x3A` | 2 bytes | Size of a section header table entry |
| `e_shnum` | `0x3C` | 2 bytes | Number of section header table entries |
| `e_shstrndx` | `0x3E` | 2 bytes | Index of section header string table |