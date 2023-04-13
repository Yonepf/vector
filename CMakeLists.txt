cmake_minimum_required(VERSION 3.23.2)
project(vector C)

set(CMAKE_C_STANDARD 11)

add_executable(vector main.c libs/data_structures/vector/vector.h libs/data_structures/vector/vector.c
        libs/data_structures/CMakeLists.txt)