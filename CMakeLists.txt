cmake_minimum_required(VERSION 3.6)
project(session12_args)

set(CMAKE_CXX_STANDARD 11)

include_directories(include_ext)

file(GLOB cpps src/*.cpp)
file(GLOB hpps src/*.hpp)

add_executable(session12_args ${cpps} ${hpps})