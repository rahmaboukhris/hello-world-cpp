cmake_minimum_required(VERSION 3.9)
project(sonar_scanner_example)

set(CMAKE_CXX_STANDARD 17)
file(GLOB SOURCES src/*.cpp)
file(GLOB SOURCES src/interf/*.cpp)
file(GLOB SOURCES src/interface/*.cpp)


add_executable(sonar_scanner_example ${SOURCES})
