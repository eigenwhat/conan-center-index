cmake_minimum_required(VERSION 3.5.0)

project(cmake_wrapper)

include(conanbuildinfo.cmake)
conan_basic_setup()

add_subdirectory("source_subfolder")
