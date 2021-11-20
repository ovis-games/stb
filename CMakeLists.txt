cmake_minimum_required(VERSION 3.12)
project(stb)

add_library(
  stb

  stb_truetype.c
)

target_include_directories(
  stb
  PUBLIC
    ${CMAKE_CURRENT_SOURCE_DIR}
)
