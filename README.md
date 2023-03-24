# Project Description
This repository is for myself to learn the cmake, which is a good tool to develop C++ project

## Dir1:cmake_learn
/cmake_learn is a basic usage of cmake, I only have one file(main.cpp) , the funciton of the file is to print "Hello world".
the step shows as follow:
'''
cd build && cmake .. && make && cd bin && ./hello
'''

## Dir2:动态库静态库相关
/动态库静态库相关  is about how to add Static and dynamic libraries when you use cmake
/动态库静态库相关/cmake_learn1 is about how to use cmake to make a Static library or dynamic library
the step about cmake_learn1 is:
cd build && cmake -DCMAKE_INSTALL_PREFIX=/usr && make

/动态库静态库相关/cmake_learn2 is about how to use a Static library or dynamic library in cmake, it's will use the library which is made by cmake_learn1
 in cmake, it's will use the library which is made by cmake_learn1
 the step about cmake_learn2 is:
 cd build && cmake .. && make && ./hello
