project(game)
add_executable(game src/main.cpp)
target_link_libraries(game ${SDL2_LIBRARY})
install(TARGETS game RUNTIME DESTINATION ${BIN_DIR})