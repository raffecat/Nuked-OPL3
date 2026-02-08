add_library(NukedOPL3 STATIC
    opl3.c
)
target_include_directories(NukedOPL3 PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
