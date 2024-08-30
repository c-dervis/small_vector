add_library (small_vector INTERFACE)

target_sources(
  small_vector
  INTERFACE
    ${CMAKE_CURRENT_SOURCE_DIR}/include/gch/small_vector.hpp
)

target_include_directories (
  small_vector
  INTERFACE
    ${CMAKE_CURRENT_SOURCE_DIR}/include
)
