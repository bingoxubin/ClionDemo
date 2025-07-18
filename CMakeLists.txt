cmake_minimum_required(VERSION 3.31)
project(ClionDemo)

set(CMAKE_CXX_STANDARD 20)

add_executable(ClionDemo main.cpp)

add_executable(main main.cpp)
add_executable(Test01 Test01/Test01.cpp)
add_executable(Test02 Test01/Test02.cpp)