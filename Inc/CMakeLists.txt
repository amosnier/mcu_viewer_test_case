add_library(app_h INTERFACE)
target_include_directories(app_h INTERFACE .)
target_link_libraries(app_h INTERFACE
        stm32g4xx_driver_h
        stm32g4xx_motor_control_h
)
target_compile_definitions(app_h INTERFACE
        STM32G431xx
        USE_FULL_LL_DRIVER
        USE_HAL_DRIVER
        ARM_MATH_CM4
)
