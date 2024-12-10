cmake_minimum_required(VERSION 3.22)
project(leet)

set(CMAKE_CXX_STANDARD 17)
add_definitions("-DKUN_DEBUG")

include_directories("src/utils")

add_executable(temp_main src/temp/main.cpp)
