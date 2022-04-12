cmake_minimum_required(VERSION 3.18 FATAL_ERROR)

project(mini_example VERSION 0.1 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

add_executable(mini_example main.cpp)
