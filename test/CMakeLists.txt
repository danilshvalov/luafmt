add_executable(test test.cpp)
target_link_libraries(test PRIVATE Catch2::Catch2WithMain)
