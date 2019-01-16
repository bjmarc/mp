# CMake build script for the cp library.

include_directories(../asl/solvers)
add_ampl_library(cp cp.cc)
target_link_libraries(cp mp)
