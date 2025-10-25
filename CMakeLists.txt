cmake_minimum_required(VERSION 3.10)

project(TD4)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED True)

include_directories(${CMAKE_CURRENT_SOURCE_DIR}/cppitertools)

file(GLOB SOURCES "*.cpp")

foreach(SOURCE ${SOURCES})
    # Get the filename without extension
    get_filename_component(EXECUTABLE_NAME ${SOURCE} NAME_WE)
    add_executable(${EXECUTABLE_NAME} ${SOURCE})
endforeach()