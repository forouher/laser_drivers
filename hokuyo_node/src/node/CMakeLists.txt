rosbuild_add_executable(hokuyo_node hokuyo_node.cpp)
target_link_libraries(hokuyo_node libhokuyo)
