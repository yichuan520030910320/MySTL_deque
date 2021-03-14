# cmake_minimum_required(VERSION <specify CMake version here>)
project(untitled)

set(CMAKE_CXX_STANDARD 14)

add_executable(untitled
        2.cpp
        utility.hpp
        deque.hpp
        exceptions.hpp
        class-bint.hpp
        class-integer.hpp
        class-matrix.hpp
        )