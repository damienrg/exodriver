find_package(PkgConfig)
pkg_check_modules(usb_library REQUIRED libusb-1.0)
include_directories(${usb_library_INCLUDE_DIRS})
  
add_library(labjackusb SHARED labjackusb.c)
target_link_libraries(labjackusb ${usb_library_LIBRARIES})

  
