##===------------------------------------------------------------------------------*- CMake -*-===##
##
##                                   S E R I A L B O X
##
## This file is distributed under terms of BSD license. 
## See LICENSE.txt for more information.
##
##===------------------------------------------------------------------------------------------===##

cmake_minimum_required(VERSION 3.12)

serialbox_add_gridtools_example(example-01-laplacian-cpp example-01-laplacian.cpp)
serialbox_add_gridtools_example(example-02-stateless-cpp example-02-stateless.cpp)
serialbox_add_gridtools_example(example-03-slice-cpp example-03-slice.cpp)

