find_package(Matplot++ REQUIRED HINTS $ENV{MATPLOTPP_DIR})

add_executable(test_matplot main.cpp)
target_link_libraries(test_matplot PRIVATE project_warnings project_options Matplot++::matplot)
