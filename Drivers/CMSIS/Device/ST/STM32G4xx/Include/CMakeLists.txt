add_library(cmsis_stm32g4xx_driver_h INTERFACE)
target_include_directories(cmsis_stm32g4xx_driver_h INTERFACE .)
target_link_libraries(cmsis_stm32g4xx_driver_h INTERFACE cmsis_h)
