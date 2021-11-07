cmake_minimum_required(VERSION 3.16)
project(cpu_performance_test)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_FLAGS "-march=native")

add_executable(${PROJECT_NAME} main.cpp)