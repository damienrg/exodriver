include_directories(${PROJECT_SOURCE_DIR}/liblabjackusb)

add_executable(u3allio u3allio.c u3.c)
target_link_libraries(u3allio labjackusb m)

add_executable(u3BasicConfigU3 u3BasicConfigU3.c u3.c)
target_link_libraries(u3BasicConfigU3 labjackusb m)

add_executable(u3EFunctions u3EFunctions.c u3.c)
target_link_libraries(u3EFunctions labjackusb m)

add_executable(u3Feedback u3Feedback.c u3.c)
target_link_libraries(u3Feedback labjackusb m)

add_executable(u3LJTDAC u3LJTDAC.c u3.c)
target_link_libraries(u3LJTDAC labjackusb m)

add_executable(u3Stream u3Stream.c u3.c)
target_link_libraries(u3Stream labjackusb m)
