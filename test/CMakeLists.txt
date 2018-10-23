include(GoogleTest)
set(TEST_FILES my_test_src.cpp)
add_executable(correrTests ${TEST_FILES})
target_link_libraries(correrTests dc-tp-base gtest_main gtest)
