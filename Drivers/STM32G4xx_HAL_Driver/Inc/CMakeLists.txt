add_library(stm32g4xx_driver_h INTERFACE)
target_include_directories(stm32g4xx_driver_h INTERFACE .)
target_link_libraries(stm32g4xx_driver_h INTERFACE
        cmsis_stm32g4xx_driver_h
        app_h
)
