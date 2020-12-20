add_executable(test_eigen main.cpp)
target_link_libraries(test_eigen PRIVATE project_warnings project_options CONAN_PKG::Eigen3)
