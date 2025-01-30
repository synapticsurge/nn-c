set(CMAKE_CXX_FLAGS "-Wall")
message("CXX Standard: ${CMAKE_CXX_STANDARD}")
project(nn-c)
add_executable(main ./src/main.c)
