cmake_minimum_required(VERSION 2.3)
project( Project_name )



#find_package( OpenCV REQUIRED )


include_directories(include_directory)

add_library(library_name SHARED
source1.cpp
source2.cpp
source3.cpp
)

add_executable( exec_name exec_source_file.cpp )


target_link_libraries( exec_name library_name -lsomething )
