cmake_minimum_required(VERSION 3.25)

project(st_motor_control_01
        VERSION 1.0
        DESCRIPTION "Motor control with STM32"
        LANGUAGES ASM C CXX)

add_subdirectory(Drivers)
add_subdirectory(Inc)
add_subdirectory(MCSDK_v6.3.2-Full)
add_subdirectory(Src)
add_subdirectory(STM32CubeIDE/Application)
