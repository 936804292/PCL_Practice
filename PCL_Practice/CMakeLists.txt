# CMake最低版本要求
CMAKE_MINIMUM_REQUIRED(VERSION 2.8)
# CMake项目名称
PROJECT(PCL_Practice)

# 设置二进制目标文件生成路径
SET(EXECUTABLE_OUTPUT_PATH ${PROJECT_BINARY_DIR}/bin)
# 设置库文件生成路径
SET(LIBRARY_OUTPUT_PATH ${PROJECT_BINARY_DIR}/lib)


# 添加四个CMake子目录
ADD_SUBDIRECTORY(./filter_pointCloud)
ADD_SUBDIRECTORY(./matrix_transform)
