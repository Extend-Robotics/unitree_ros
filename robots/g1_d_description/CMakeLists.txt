cmake_minimum_required(VERSION 3.0.2)
project(g1_d_description)

find_package(catkin REQUIRED)

catkin_package()

install(DIRECTORY meshes
        DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})

install(FILES g1_d_with_dex1_1.urdf
        DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
