cmake_minimum_required(VERSION 3.12)
project(Risc_V)

set(CMAKE_CXX_STANDARD 14)

add_executable(Risc_V main.cpp Simulator.cpp Simulator.h)