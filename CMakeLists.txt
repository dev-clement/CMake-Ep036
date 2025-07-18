cmake_minimum_required(VERSION 3.28)

project(CppProjectTemplate
        VERSION 0.0.1
        LANGUAGES C CXX)

set(CMAKE_CXX_STANDARD          17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS       OFF)

set(LIBRARY_NAME Library)
set(EXECUTABLE_NAME Executable)


add_subdirectory(configure/)
add_subdirectory(my_lib/)
add_subdirectory(app/)
