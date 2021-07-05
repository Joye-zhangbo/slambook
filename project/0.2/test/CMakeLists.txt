find_package( OpenCV 4.2 REQUIRED )

add_executable( run_vo run_vo.cpp )
target_link_libraries( run_vo myslam )