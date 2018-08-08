cmake_minimum_required(VERSION 3.2)

set(CMAKE_MODULE_PATH ${CMAKE_MODULE_PATH} ${CMAKE_CURRENT_SOURCE_DIR}/cmake-modules)

set(APP_NAME helloWorld)
project(${APP_NAME})

set (CMAKE_CXX_STANDARD 11)

add_executable(${APP_NAME} HelloWorld.cpp)

set(SECOND_EXECUTABLE second)
add_executable(${SECOND_EXECUTABLE} second.cpp)