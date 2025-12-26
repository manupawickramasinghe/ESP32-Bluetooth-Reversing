cmake_minimum_required(VERSION 3.16)

include($ENV{IDF_PATH}/tools/cmake/project.cmake)

# Disable the "Trim" build.
idf_build_set_property(MINIMAL_BUILD OFF)

project(esp32-bluetooth-golden-binary)
