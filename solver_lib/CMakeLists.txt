cmake_minimum_required(VERSION 3.4)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} --std=c++11")
set(CMAKE_CXX_STANDARD_REQUIRED ON)
add_library(solver STATIC solver.cpp)
