cmake_minimum_required(VERSION 3.10.2)
project(magicbot-gen1_description)

find_package(ament_cmake REQUIRED)

ament_package()

install(DIRECTORY
  launch meshes urdf rviz
  DESTINATION share/${PROJECT_NAME}
)
