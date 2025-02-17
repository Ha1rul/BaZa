cmake_minimum_required(VERSION 3.29)
project(BaZa C)

set(CMAKE_C_STANDARD 11)

add_executable(BaZa main.c
        interface.cpp)
