cmake_minimum_required(VERSION 3.22)

project(Helloworld LANGUAGES CXX C)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

add_executable(main
    src/main.cpp
    src/HW.cpp
)
target_include_directories(main PRIVATE include)

