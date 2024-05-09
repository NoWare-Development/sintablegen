cmake_minimum_required(VERSION 3.5)

set(PROJECT_NAME sintablegen)
project(${PROJECT_NAME} LANGUAGES C)

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -O3 -fPIC")

set(SOURCES
  "${CMAKE_CURRENT_SOURCE_DIR}/src/main.c"
  )

add_executable(${PROJECT_NAME} ${SOURCES})

target_link_libraries(${PROJECT_NAME} PUBLIC m)
