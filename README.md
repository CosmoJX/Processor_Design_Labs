# Processor_Design_Labs
Contains the lab notes

## Lab 1: CMake and Toolchain
### CMake version:
cmake version 3.22.1

### CMake Targets:
... all (the default if no target is provided)\
... clean (clean all related files produced in compilation)\
... depend\
... edit_cache\
... rebuild_cache\
... hello_world\
... hello.o (machine code)\
... hello.i (preprocessed source code)\
... hello.s (x86 assembly)

### Post-Lab Questions
- paths are relative to the current directory where the CMakeLists.txt lives
- CMake is a meta-build system and Ninja is a build system. CMake is used to generate Ninja build files. 
- Run cmake in a separate directory can prevent the intermediate files generated in the building process from polluting the main directory. 

