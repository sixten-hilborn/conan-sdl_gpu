cmake_minimum_required(VERSION 2.8)
project(conan-sdl-gpu)

include(conanbuildinfo.cmake)
conan_basic_setup()

add_subdirectory("./source_subfolder")
