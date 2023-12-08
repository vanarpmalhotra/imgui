cmake_minimum_required(VERSION 3.26)
project(imgui)

set(CMAKE_CXX_STANDARD 17)

set(SOURCE_FILES
        imgui.cpp
        imgui_demo.cpp
        imgui_draw.cpp
        imgui_tables.cpp
        imgui_widgets.cpp
)

add_library(${PROJECT_NAME} STATIC ${SOURCE_FILES})
