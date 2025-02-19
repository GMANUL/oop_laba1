cmake_minimum_required(VERSION 3.20)

project(misis2025_oop)

set_property(GLOBAL PROPERTY USE_FOLDERS ON)
set_property(GLOBAL PROPERTY PREDEFINED_TARGETS_FOLDER "cmake")
set_property(GLOBAL PROPERTY CXX_STANDARD 20)

include_directories(src)
add_executable(main src/main.cpp)