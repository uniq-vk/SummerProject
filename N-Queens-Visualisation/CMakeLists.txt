cmake_minimum_required(VERSION 3.10)

# Set the project name
project(nqueens)

# Add an executable
add_executable(nqueens main.cpp)

# Include directories
include_directories(/usr/include /usr/include/GL)

# Link libraries
target_link_libraries(nqueens GL glut GLU m)
