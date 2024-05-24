#
#

cmake_minimum_required(VERSION 3.7)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

project(public-repo-test)

set(SRC main.cpp)

add_executable(${PROJECT_NAME} ${SRC})
