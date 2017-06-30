cmake_minimum_required(VERSION 2.8)

project (2_LabEightComplexNumbersAddition_example)
set(SOURCES Source.cpp)
add_executable (${PROJECT_NAME} ${SOURCES})
target_link_libraries(${PROJECT_NAME} 2_LabEightComplexNumbersAddition)
