include(GoogleTest)
file(GLOB TEST_FILES
  "${CMAKE_SOURCE_DIR}/test/*.h"
  "${CMAKE_SOURCE_DIR}/test/*.cpp"
)
add_executable(correrTests ${TEST_FILES})
target_link_libraries(correrTests dc-tp-base gtest_main gtest)
