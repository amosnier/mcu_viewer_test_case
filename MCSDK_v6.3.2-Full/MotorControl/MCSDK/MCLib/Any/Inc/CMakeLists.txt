add_library(motor_control_h INTERFACE)
target_include_directories(motor_control_h INTERFACE .)

# Files in this directory assume the reachability of header files that are used
# for functionality configuration, and that typically are stored by ST at the
# top application source code level. We handle that situation by requiring the
# availability of an application header library in the project.
target_link_libraries(motor_control_h INTERFACE app_h)
