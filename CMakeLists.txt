project(easyframes)

cmake_minimum_required(VERSION 2.4)

add_definitions(-Wall)
include_directories(src)

add_executable(er src/er.c)

add_executable(base64decode src/base64decode.c)

install(TARGETS er base64decode DESTINATION bin)
