---
authors:
  - AE
  - "0x4248"
tags:
  - Software
  - Programming
aliases:
  - libraries
  - libs
---
**Libraries** are collections of precompiled code deigned to simplify and optimise specific tasks
## Dynamic libraries:

This type of libraries are supposed to be used by lots of [[Program|programs]] but are not added to the executable at compile time.
These libraries are usually in a central location.
E.G: `/usr/local/lib` on most [[UNIX]] systems

The standard file extensions are:
- [[Microsoft windows|Windows]]: [[dll|.dll]]
- [[MacOS]]: [[dylib|.dylib]]
- [[Linux]] and other [[UNIX]] systems: [[so|.so]]

Often to link this type of library to a compiler you need to specify the path to the file the library is in with -L and then specify the name of the library with -l; if the library name has lib at the start don't add that to the flag
E.G: `clang++ test.cpp -L libraries -l Test`
The file name of the library is `libTest.dylib`.

## Static libraries:

This type of library is usually added within the project and is compiled with the program
But is not shared between multiple programs
The standard file extensions are:
- [[Microsoft windows|Windows]]: [[lib|.lib]]
- [[UNIX]]: [[a|.a]]

Often to link this type of library to a compiler all you need to do is add the file in the command
E.G: `clang++ test.cpp libraries/libTest.a`