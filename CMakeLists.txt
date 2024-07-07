cmake_minimum_required(VERSION 3.26)

project(cobs-c LANGUAGES C)

add_library(cobs-c STATIC
    "cobs.c"
    "cobsr.c
)

target_include_directories(cobs-c PUBLIC .)
