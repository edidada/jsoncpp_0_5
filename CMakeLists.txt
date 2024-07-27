cmake_minimum_required(VERSION 3.12)
project(jsoncpp_0_5)

set(CMAKE_CXX_STANDARD 11)

add_subdirectory(src/lib_json)
add_subdirectory(src/jsontestrunner)
add_subdirectory(src/test_lib_json)
