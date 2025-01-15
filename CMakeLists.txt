cmake_minimum_required(VERSION 3.29)
project(3207_Lab_Introduction_F24_ C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(3207_Lab_Introduction_F24_
    header.h
    print_random.c
    random.c)
