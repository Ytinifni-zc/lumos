file(GLOB LUMOS_EXE ${CMAKE_CURRENT_SOURCE_DIR}/*.cpp)

add_executable(pagerank pagerank.cpp)
add_executable(pagerank_delta pagerank_delta.cpp)
add_executable(pagerank_gg pagerank_gg.cpp)
