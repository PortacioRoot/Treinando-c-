cmake_minimum_required(VERSION 3.0)
project(template)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
add_executable(${PROJECT_NAME} WIN32 MACOSX_BUNDLE template.cpp)
set_target_properties(${PROJECT_NAME} PROPERTIES FOLDER "Exemplos")

