cmake_minimum_required(VERSION 3.21)
project(PA1_Public)

set(CMAKE_CXX_STANDARD 14)

add_executable(PA1_Public main.cpp lex.cpp lex.h val.h val.cpp parseInt.h parseInt.cpp)
