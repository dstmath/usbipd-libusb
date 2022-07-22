cmake_minimum_required(VERSION 3.0.2)


set(LIBUSB_DIR ${CMAKE_CURRENT_SOURCE_DIR}/libusb)



set(ENABLE_PROGRAMS OFF)
set(ENABLE_TESTING OFF)

set(BUILD_SHARED_LIBS OFF CACHE BOOL "Static only" FORCE)

add_subdirectory(${LIBUSB_DIR})