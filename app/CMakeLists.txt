set(PINETIME_DIR ${CMAKE_CURRENT_LIST_DIR} CACHE PATH "Hypnos root directory")

zephyr_include_directories(include)

add_subdirectory(drivers/sensor)
add_subdirectory(subsys)
