cmake_minimum_required(VERSION 3.10)
project(MsiKeyboardLedController)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11 -Wall")

set(SOURCE_FILES main.cpp)

add_executable(MsiKeyboardLedController ${SOURCE_FILES})
