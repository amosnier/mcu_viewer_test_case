add_library(stm32g4xx_motor_control
        r3_2_g4xx_pwm_curr_fdbk.c
)
target_link_libraries(stm32g4xx_motor_control PUBLIC stm32g4xx_motor_control_h)
