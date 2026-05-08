cmake_minimum_required(VERSION 3.10)
project(hello_c C)

set(CMAKE_C_STANDARD 99)
set(CMAKE_C_STANDARD_REQUIRED ON)

add_executable(hello main.c)
