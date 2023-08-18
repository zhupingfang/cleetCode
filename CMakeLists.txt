cmake_minimum_required(VERSION 3.26)
project(test)

set(CMAKE_CXX_STANDARD 17)


#包含cpp文件i

add_subdirectory(src)


#添加头文件搜索路径
include_directories(${CMAKE_SOURCE_DIR}/include)

add_executable(test main.cpp ${SOURCE})

#获取cpp文件资源
#target_link_libraries( test src)