add_library(mere-tdd "")

target_sources(mere-tdd PUBLIC
Test.h)

set_target_properties(mere-tdd PROPERTIES LINKER_LANGUAGE CXX)

target_include_directories(mere-tdd PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
