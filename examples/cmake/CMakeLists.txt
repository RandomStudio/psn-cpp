add_executable(example_send psn_server.cpp)

set_property(TARGET example_send PROPERTY CXX_STANDARD 11)

target_include_directories(example_send PUBLIC ../../include)