# Cimple-Compiler
Compiles from a language ```cimple``` to MIPS assembly. 
## Cimple Language 
The language ```cimple``` is defined by the files ```files/cimple.cup``` which defines the language syntax and ```files/cimple.jlex``` defines the language tokens and reserve words.
## Running the Program
In the command line, go into the ```files``` folder. Run the command ```make``` to compile the project. To run the compiler, enter ```make test``` which takes in a cimple file named ```hello.cimple``` and returns a MIPS file ```mips_code.s```. To delete the compile generated files, run ```make clean```.
