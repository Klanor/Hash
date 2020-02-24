cmake_minimum_required(VERSION 3.15)
project(ClassWork)

set(CMAKE_CXX_STANDARD 14)

add_executable(HashMap HashMap/HashMap.cpp Header.h)
add_executable(LinearHash LinearHash/LinearHash.cpp Header.h)