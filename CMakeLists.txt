project(proj)

find_package(OpenCV)

include_directories(${OpenCV_INCLUDE_DIRS})
add_executable(cv2_yuv2rgb cv2_yuv2rgb.cpp)
target_link_libraries(cv2_yuv2rgb ${OpenCV_LIBS})
