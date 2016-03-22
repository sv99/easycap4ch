cmake_minimum_required(VERSION 3.3)
project(somagic_easycap_1_1)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    somagic-audio-capture.c
    somagic-both.c
    somagic-capture.c
    somagic-init.c)

add_executable(somagic_easycap_1_1 ${SOURCE_FILES})