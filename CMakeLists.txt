cmake_minimum_required(VERSION 3.16.0)

if (NOT DEFINED PROJECT_NAME)
    include($ENV{IDF_PATH}/tools/cmake/project.cmake)
    project(vst-generic)
else ()
    idf_component_register(INCLUDE_DIRS .)
endif (NOT DEFINED PROJECT_NAME)
