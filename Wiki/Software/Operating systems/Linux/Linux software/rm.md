---
authors: 
  - "0x4248"
tags:
  - Software
  - Operating_systems
  - Linux
  - Linux_software
---
The `rm` command in [[Linux]] and [[UNIX]] removes a file.

## Example
Here we use the [[ls]] command to see the files in our directory. Then we delete `file_1`. To delete loads of files at once we can use a wildcard. A wildcard allows us to select all files that mach a start or end pattern or even all files.
```
admin@raspberrypi:~/temp $ ls
file_1   file_2  file_4  file_6  file_8  other_file_1  other_file_3
file_10  file_3  file_5  file_7  file_9  other_file_2  other_file_4
admin@raspberrypi:~/temp $ rm file_1
admin@raspberrypi:~/temp $ ls
file_10  file_3  file_5  file_7  file_9        other_file_2  other_file_4
file_2   file_4  file_6  file_8  other_file_1  other_file_3
admin@raspberrypi:~/temp $ rm file_*
admin@raspberrypi:~/temp $ ls
other_file_1  other_file_2  other_file_3  other_file_4
admin@raspberrypi:~/temp $ rm *
admin@raspberrypi:~/temp $ ls
admin@raspberrypi:~/temp $
```

## Usage
```
Usage: rm [OPTION]... [FILE]...
Remove (unlink) the FILE(s).

  -f, --force           ignore nonexistent files and arguments, never prompt
  -i                    prompt before every removal
  -I                    prompt once before removing more than three files, or
                          when removing recursively; less intrusive than -i,
                          while still giving protection against most mistakes
      --interactive[=WHEN]  prompt according to WHEN: never, once (-I), or
                          always (-i); without WHEN, prompt always
      --one-file-system  when removing a hierarchy recursively, skip any
                          directory that is on a file system different from
                          that of the corresponding command line argument
      --no-preserve-root  do not treat '/' specially
      --preserve-root[=all]  do not remove '/' (default);
                              with 'all', reject any command line argument
                              on a separate device from its parent
  -r, -R, --recursive   remove directories and their contents recursively
  -d, --dir             remove empty directories
  -v, --verbose         explain what is being done
      --help        display this help and exit
      --version     output version information and exit

By default, rm does not remove directories.  Use the --recursive (-r or -R)
option to remove each listed directory, too, along with all of its contents.

To remove a file whose name starts with a '-', for example '-foo',
use one of these commands:
  rm -- -foo

  rm ./-foo

Note that if you use rm to remove a file, it might be possible to recover
some of its contents, given sufficient expertise and/or time.  For greater
assurance that the contents are truly unrecoverable, consider using shred(1).

GNU coreutils online help: <https://www.gnu.org/software/coreutils/>
Full documentation <https://www.gnu.org/software/coreutils/rm>
or available locally via: info '(coreutils) rm invocation'
```