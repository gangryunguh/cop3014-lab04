cmake_minimum_required(VERSION 3.08)
project(cop3014_lab04)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES grades.cpp initialize.cpp LogicalOp.cpp switch.cpp)

add_executable(grades.exe grades.cpp)
add_executable(initialize.exe initialize.cpp)
add_executable(LogicalOp.exe LogicalOp.cpp)
add_executable(switch.exe switch.cpp)
