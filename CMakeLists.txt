project(easyframes)

cmake_minimum_required(VERSION 2.4)

add_definitions(-Wall)
include_directories(src)

add_executable(er src/er.c)

install(TARGETS er DESTINATION bin)
