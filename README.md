# Shell
All the shells that I have made.

I do not take responsibility for any damage that occurs. You can only trust it's safe by looking at the code and that I use these

Put them in any of your bin directories for easy use.
## Compile C
This will include all directories (recursively) for the inclusion ```-I``` flag, so you can include all headers by the file name, and not have to worry about directories. Also compiles all .cpp files in a project folder. You can choose any compiler, then the output file name, and also include other flags you want such as library flags. Works for C and C++.

Example
```shell
#Example
$ compilec bonanzo -lSDL2
```
Note: I now use the CMake build system, it is better than this, I don't use this anymore

## Fixres
I have a 2nd monitor from an obscure brand and the screen is always way to small. This script automates fixing it and setting its resolution to something actually usable.
