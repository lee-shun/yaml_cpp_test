cmake_minimum_required(VERSION 2.6)
set (CMAKE_CXX_STANDARD 11)
project(test_yaml)
add_executable(${PROJECT_NAME} "yaml_test.cpp")

# add_subdirectory(yaml-cpp)
# include_directories(${CMAKE_SOURCE_DIR}/yaml-cpp/include)
target_link_libraries(${PROJECT_NAME} yaml-cpp)
