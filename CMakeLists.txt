cmake_minimum_required(VERSION 2.8 FATAL_ERROR)
project(Keypad_kristof)

add_executable(Keypad_kristof main.c)

target_link_libraries(Keypad_kristof PJ_RPI)
