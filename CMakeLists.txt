cmake_minimum_required(VERSION 3.7)

set(CMAKE_CXX_STANDARD 17)

project(envoy-stat)

add_executable(
    ${PROJECT_NAME} src/main.cpp
)
