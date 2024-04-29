---
authors: 
  - "0x4248"
tags:
  - Software
  - Operating_systems
  - Linux
  - Linux_software
---
In [[Linux]] and [[UNIX]] the `mkdir` command creates directories.

## Example 
Here we create the folders `test_folder` and `folder_1`, `folder_2` and see the result using [[ls]].
```
admin@raspberrypi:~/temp $ mkdir test_folder
admin@raspberrypi:~/temp $ ls
test_folder
admin@raspberrypi:~/temp $ mkdir folder_1 folder_2
admin@raspberrypi:~/temp $ ls
folder_1  folder_2  test_folder
admin@raspberrypi:~/temp $
```
## Usage
```
Usage: mkdir [OPTION]... DIRECTORY...
Create the DIRECTORY(ies), if they do not already exist.

Mandatory arguments to long options are mandatory for short options too.
  -m, --mode=MODE   set file mode (as in chmod), not a=rwx - umask
  -p, --parents     no error if existing, make parent directories as needed,
                    with their file modes unaffected by any -m option.
  -v, --verbose     print a message for each created directory
  -Z                   set SELinux security context of each created directory
                         to the default type
      --context[=CTX]  like -Z, or if CTX is specified then set the SELinux
                         or SMACK security context to CTX
      --help        display this help and exit
      --version     output version information and exit

GNU coreutils online help: <https://www.gnu.org/software/coreutils/>
Full documentation <https://www.gnu.org/software/coreutils/mkdir>
or available locally via: info '(coreutils) mkdir invocation
```