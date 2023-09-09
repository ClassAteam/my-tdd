add_library(logging "")

target_sources(logging PUBLIC
Log.h)

set_target_properties(logging PROPERTIES LINKER_LANGUAGE CXX)

add_subdirectory(tests)
