# Example of using CMake to create a cross-platform CUDA c++ project

***

This is an example of building a CUDA C++ project with CMake, you need to install the following tools in advance :

- CUDA Toolkit
- CMake
- C/C++ compiler

The include folder contains the headers, the src folder contains the source files.

```
.
├─include
│  ├─
├─src
│  ├─
└─CMakeLists.txt
```

To build another project, just copy all the source files to the src folder, copy all the headers to the include folder, and enable the appropriate options in CMakeLists.txt depending on the cuda library being called.

You can view the specific article : [ZhiHu/CX98](https://zhuanlan.zhihu.com/p/701581020) or [CX](https://cx9898.github.io/post/yong-%20CMake%20-gou-jian-kua-ping-tai-%20CUDA%20C-C%2B%2B%20-xiang-mu.html)

***

## Build

### Linux

The Linux examples are built using CMake.   To use CMake, change the current directory to the example directory you wish to build, create and go to the build folder, and run `cmake ..` and `make` :

```Shell
$ cd <cmake-cuda-sample>
$ mkdir build
$ cd build
$ cmake ..
$ make
```

***

### Window

The Window examples are built using CMake. Install the CMake Window version to build.

***

