add_library(hardware_divider INTERFACE)
target_sources(hardware_divider INTERFACE ${CMAKE_CURRENT_LIST_DIR}/divider.S)
target_include_directories(hardware_divider INTERFACE ${CMAKE_CURRENT_LIST_DIR}/include)
target_link_libraries(hardware_divider INTERFACE hardware_structs)