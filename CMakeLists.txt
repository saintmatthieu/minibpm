add_library(MiniBpm
  src/MiniBpm.cpp
)

target_include_directories(MiniBpm
  PUBLIC
    ${CMAKE_CURRENT_SOURCE_DIR}/src
)