cmake_minimum_required(VERSION 3.2)
project(stk1160)

include_directories(
    BEFORE /Users/svolkov/work/rpi/linux-592503752b6951972f161f04280683c5af38d173/include
    BEFORE /Users/svolkov/work/rpi/rpi-cross-docker/rootfs/usr/include)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    stk1160-ac97.c
    stk1160-core.c
    stk1160-i2c.c
    stk1160-reg.h
    stk1160-v4l.c
    stk1160-video.c
    stk1160.h)

add_executable(stk1160 ${SOURCE_FILES})