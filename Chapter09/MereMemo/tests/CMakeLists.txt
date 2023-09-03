add_executable(first_test "")

target_sources(first_test PRIVATE
  Construction.cpp
  Util.cpp
  Util.h
  main.cpp
)

target_link_libraries(first_test PRIVATE logging)
target_link_libraries(first_test PRIVATE mere-tdd)
