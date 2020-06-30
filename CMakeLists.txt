cmake_minimum_required (VERSION 3.6.0)

SET(CMAKE_CXX_FLAGS "-std=c++11 -O3")

project(felix-long-readout-tools CXX)

add_executable(dumpfile-to-text dumpfile-to-text.cpp PdspChannelMapService.cpp)

add_executable(check-timestamps check-timestamps.cpp)
