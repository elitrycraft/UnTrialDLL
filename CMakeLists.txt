cmake_minimum_required(VERSION 3.20)
project(Untrial LANGUAGES C)

add_library(Untrial SHARED
    src/dllmain.c
    Untrial.def
    version.rc
)

set_target_properties(Untrial PROPERTIES
    OUTPUT_NAME "Untrial"
)