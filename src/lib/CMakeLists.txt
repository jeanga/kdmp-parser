# Axel '0vercl0k' Souchet - April 18 2020
add_library(kdmp-parser kdmp-parser.cc)
target_include_directories(kdmp-parser PUBLIC
    $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}>
    $<INSTALL_INTERFACE:>  # <prefix>/include/
)
