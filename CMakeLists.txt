project(roomGenerator)

cmake_minimum_required(VERSION 3.16)

set(SOURCES
  ./realization/Source/main.cpp
  )

add_executable(${PROJECT_NAME} ${SOURCES})
