cmake_minimum_required(VERSION 3.3)
project(chap12)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp str.cpp str.h)
add_executable(chap12 ${SOURCE_FILES})