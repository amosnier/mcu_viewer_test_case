add_library(motor_control
        bus_voltage_sensor.c
        circle_limitation.c
        digital_output.c
        mcpa.c
        ntc_temperature_sensor.c
        open_loop.c
        pid_regulator.c
        pqd_motor_power_measurement.c
        r_divider_bus_voltage_sensor.c
        ramp_ext_mngr.c
        revup_ctrl.c
        speed_pos_fdbk.c
        speed_torq_ctrl.c
        sto_pll_speed_pos_fdbk.c
        virtual_speed_sensor.c
)
target_link_libraries(motor_control PUBLIC motor_control_h)
