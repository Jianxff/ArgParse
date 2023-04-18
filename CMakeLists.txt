cmake_minimum_required(VERSION 3.25)
project(argParse)

set(CMAKE_CXX_STANDARD 14)

include_directories(source)

add_executable(argParse
        source/argparse.hpp
        test/test.cpp)
