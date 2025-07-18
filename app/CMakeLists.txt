set(SOURCES
    ./src/main.cpp
)

add_executable(${EXECUTABLE_NAME} ${SOURCES})
target_link_libraries(${EXECUTABLE_NAME} PUBLIC ${LIBRARY_NAME})
target_include_directories(${EXECUTABLE_NAME} PUBLIC ./include/)
