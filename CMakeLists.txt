cmake_minimum_required(VERSION 4.0)
project(week_11_wed_lab_KGhim7)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(week_11_wed_lab_KGhim7
        DoubleHashing.hpp
        HashTableClosed.hpp
        HashTableClosed.tpp
        LinearProbing.hpp
        QuadraticProbing.hpp
        Week11-Wed-Lab.cpp)
