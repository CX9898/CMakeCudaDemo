# Example of creating a CUDA C++ project using CMake

***

This is an example of building a CUDA C++ project with CMake, you need to install the following tools in advance :
- CUDA Toolkit
- CMake
- C/C++ compiler. Windows uses visual studio; Linux uses gcc/g++

The include folder contains the headers, the src folder contains the source files, and the Common folder contains some common CUDA-friendly headers from NVIDIA's official cuda-samples.
```
.
├─Common
├─include
│  ├─
└─src
│  ├─
└─CMakeLists.txt
```

## Build

### Linux

The Linux examples are built using CMake.   To use CMake, change the current directory to the example directory you wish to build, create and go to the build folder, and run `cmake ..` and `make` :

```Shell
$ cd <CMakeCudaDemo>
$ mkdir build
$ cd build
$ cmake ..
$ make
```
