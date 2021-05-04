cmake_minimum_required(VERSION 3.10)

find_package(ROOT)

project(main)

add_executable(main main.cpp)

enable_testing()
add_test(NAME main COMMAND main)
