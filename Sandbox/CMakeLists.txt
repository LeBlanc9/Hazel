aux_source_directory(src SRC_LIST)
add_executable(Sandbox ${SRC_LIST})


include_directories(${PROJECT_SOURCE_DIR}/Hazel/src/)
target_link_libraries(Sandbox Hazel)

add_compile_definitions(HZ_PLATFORM_WINDOWS)