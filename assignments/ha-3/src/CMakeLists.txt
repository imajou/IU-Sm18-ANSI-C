cmake_minimum_required(VERSION 3.8)
project(src C)
set(CMAKE_C_STANDARD 99)

set(SOURCE_FILES bitMap.c bitMap.h)
add_executable(src ${SOURCE_FILES})