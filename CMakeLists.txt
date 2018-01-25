cmake_minimum_required(VERSION 3.9)
project(skiplist)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        skiplist.h
        skiplist_test.c)

add_executable(skiplist ${SOURCE_FILES})
