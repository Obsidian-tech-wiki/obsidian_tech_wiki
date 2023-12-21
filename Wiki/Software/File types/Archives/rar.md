---
authors:
  - Lewis Evans
tags:
    - Software
    - File_types
aliases:
    - .rar
    - .r00
    - .r01
    - .rev
Magic_numbers:
    - 52 61 72 21 1A 07 00 (Rar!)
    - 52 61 72 21 1A 07 01 00 (Rar!)
---
**.rar** ([[RAR Archive]]) A file compression format that supports data compression, error recovery, and file spanning. It is primarily used in the Windows application [[WinRAR]] and is not open source. It is also supported by the open source [[7-Zip]].

## Features
RAR archives have many features, including:
- Data compression
- Error recovery
- File spanning
- NTFS symbolic and hard links
- Unicode file names
- Password protection
- File comments

## Other File Extensions
The `.rar` is the main file extension for RAR archives, but there are other file extensions that are used for RAR archives. These are:
- `.r00`
- `.r01`
- `.rev`

### `.r00` and `.r01`
The `.r00` and `.r01` extensions are used for split RAR archives. These files are used to split a RAR archive into multiple files. The `.r00` file is the first file in the split archive, and the `.r01` file is the second file in the split archive. The `.r00` file is created when the RAR archive is created.

### `.rev`
The `.rev` extension is used for data recovery files. These files are used to recover data from a RAR archive if the main file is damaged or corrupted. The `.rev` file is created when the RAR archive is created.


## Magic Numbers
The magic numbers for RAR archives are:
- `52 61 72 21 1A 07 00` (Rar!)
- `52 61 72 21 1A 07 01 00` (Rar!)

The `52 61 72 21 1A 07 00` magic number was used for RAR archives created before RAR 5.0. The `52 61 72 21 1A 07 01 00` magic number was used for RAR archives created after RAR 5.0.

