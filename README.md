# C/C++ project template with Unit Tests

This is a basic template to create a C/C++ project. Compilation process is handled by [CMake](https://cmake.org/). Unit tests are provided by [Google Test](https://github.com/google/googletest). The Google Test libraries will be downloaded and built by CMake.

## Requirements
+ CMake
+ A C/C++ compiler.

## How to use this template
1. Put all header files on `include/` folder. Source files go inside `src/`.
2. Go into the `CMakeLists.txt` file and change the project name. Also, include all your source files in this file. 
3. For the `CMakeLists.txt` inside the `tests` folder, include the unit tests source files and also the project source files.

## How to compile my project
Go into your project root folder and run these commands:
```bash
mkdir build
cd build
cmake ..
make
```

The executable for the program and the unit tests will be in the `bin/` folder.
