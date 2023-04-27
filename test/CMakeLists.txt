add_executable(video_test testcase.cc)
find_package(Catch2 3 REQUIRED)
target_link_libraries(video_test PRIVATE Catch2::Catch2WithMain)