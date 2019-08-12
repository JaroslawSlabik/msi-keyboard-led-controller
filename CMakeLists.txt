cmake_minimum_required(VERSION 3.10)

if(UNIX)
    message("This is a ${CMAKE_SYSTEM_NAME} system")
elseif(WIN32)
    message("This is a Windows System")
endif()

set(EXECUTABLE_OUTPUT_PATH ${PROJECT_BINARY_DIR}/bin)
set(SOURCE_DIR ${PROJECT_SOURCE_DIR}/src)

add_subdirectory(src)

#https://github.com/kigster/cmake-project-template/blob/master/src/CMakeLists.txt
