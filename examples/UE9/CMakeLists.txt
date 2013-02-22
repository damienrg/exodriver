include_directories(${PROJECT_SOURCE_DIR}/liblabjackusb)

add_executable(ue9allio ue9allio.c ue9.c)
target_link_libraries(ue9allio labjackusb m)

add_executable(ue9BasicCommConfig ue9BasicCommConfig.c ue9.c)
target_link_libraries(ue9BasicCommConfig labjackusb m)

add_executable(ue9ControlConfig ue9ControlConfig.c ue9.c)
target_link_libraries(ue9ControlConfig labjackusb m)

add_executable(ue9EFunctions ue9EFunctions.c ue9.c)
target_link_libraries(ue9EFunctions labjackusb m)

add_executable(ue9EthernetExample ue9EthernetExample.c ue9.c)
target_link_libraries(ue9EthernetExample labjackusb m)

add_executable(ue9Feedback ue9Feedback.c ue9.c)
target_link_libraries(ue9Feedback labjackusb m)

add_executable(ue9LJTDAC ue9LJTDAC.c ue9.c)
target_link_libraries(ue9LJTDAC labjackusb m)

add_executable(ue9SingleIO ue9SingleIO.c ue9.c)
target_link_libraries(ue9SingleIO labjackusb m)

add_executable(ue9Stream ue9Stream.c ue9.c)
target_link_libraries(ue9Stream labjackusb m)

add_executable(ue9TimerCounter ue9TimerCounter.c ue9.c)
target_link_libraries(ue9TimerCounter labjackusb m)
