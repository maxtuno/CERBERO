cmake_minimum_required(VERSION 2.4)
project(cerberus)

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${PROJECT_SOURCE_DIR}/bin)

set(CMAKE_CC_STANDARD 89)

add_executable(cerbero cerbero.c)
