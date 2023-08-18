

#添加头文件位置
include_directories(${PROJECT_SOURCE_DIR}/include)

#添加资源到库
aux_source_directory(${CMAKE_CURRENT_SOURCE_DIR} SOURCE)

add_library(src ${SOURCE})

