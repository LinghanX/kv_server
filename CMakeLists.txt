cmake_minimum_required(VERSION 3.7)
project(kv_server)

include_directories(include)
set(CMAKE_CXX_STANDARD 11)

add_executable(kv_server main.cpp)