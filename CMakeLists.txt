cmake_minimum_required(VERSION 2.0)

project(glad)

add_library(${PROJECT_NAME} 
    PUBLIC  
    ${CMAKE_CURRENT_SOURCE_DIR}/src/glad.c
)

target_include_directories(${PROJECT_NAME} 
    PUBLIC 
    ${CMAKE_CURRENT_SOURCE_DIR}/include/
)