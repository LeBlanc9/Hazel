aux_source_directory(src/Hazel SRC_LIST)
add_library(Hazel SHARED ${SRC_LIST})

add_compile_definitions(HZ_PLATFORM_WINDOWS)
add_compile_definitions(HZ_BUILD_DLL)