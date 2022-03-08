cmake_minimum_required(VERSION 3.16)
project(deeper)

set(CMAKE_CXX_STANDARD 20)

add_executable(deeper deeper.c gpio.c)
target_link_libraries(deeper pthread)
