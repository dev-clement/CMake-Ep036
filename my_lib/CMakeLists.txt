set(SOURCES
    ./src/my_lib.cpp
)

set(HEADERS
    ./include/my_lib.hpp
)

add_library(${LIBRARY_NAME} STATIC ${SOURCES} ${HEADERS})
target_include_directories(
    ${LIBRARY_NAME}
    PUBLIC
    ./include/
    ${CMAKE_BINARY_DIR}/configured_files/include
)
