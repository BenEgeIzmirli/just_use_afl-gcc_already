# just_use_afl-gcc_already
For when you are sick of digging through the depths of obscure build system configuration files and just want EVERYTHING to compile with afl-gcc.

This is a very simple script, but I'm sick of inventing it from scratch every time I need to fuzz something, so here it is.

## Usage
1. Rename your current gcc binary (found with `which gcc` or `whereis gcc`) to gcc-real
2. Copy the bash script into that same directory, and name it `gcc`
3. Everything that uses gcc will compile with afl-gcc instead :)
